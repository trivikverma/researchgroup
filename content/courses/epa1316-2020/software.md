---
title: Software
linktitle: Software
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  epa1316-2020:
    name: Software
    weight: 70

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
# weight: 1
---

This course is best followed if you can reproduce the examples and tutorials provided with it. To do so, you will need to install in your machine a series of software packages. These are all open-source and available for free to download.

There are two main pathways to install required Python libraries on your machine. A minimalist one is less stable and will only provide Python resources, while a more comprehensive one will install not only a Python stack but also several useful libraries. If you want to learn to explore Python and its capabilities, while going beyond just this course, I recommend option 1. Option 2 is beneficial for this course but does not allow you to install new libraries, which means you are limited by what it offers (it is still powerful, so you will not be limited in any way).


## 1) A minimalist approach: `conda` (recommended)

If you want a more minimalist installation that *only* includes the barebones of what's needed in this context, and/or you are not running Windows 10 Pro, macOS or Linux, the recommended approach is to do a `conda` installation. This route will install a Python distribution natively with the libraries we will need. Please note that no interactive extensions or R packages are installed in this case, and also be aware the installation is less stable as it relies on the specific versions for your OS and latest releases. In most cases, it should be fine, and this particular stack is regularly tested, but some failures nevertheless happen sometimes.

To install Python and required libraries through this approach, please follow these steps:

- Install [`miniconda`](https://docs.conda.io/en/latest/miniconda.html) for your OS version from the [official link](https://docs.conda.io/en/latest/miniconda.html). Make sure to install the Python 3 (e.g. 3.8) version, not Python 2.
- Once you have miniconda installed, we need to set up an independent environment that isolates all the functionality we need.

But first, what are environments and do I need them?

Environments in Python are like sandboxes that have different versions of Python and/or packages installed in them. You can create, export, list, remove, and update environments. Switching or moving between environments is called activating the environment. When you are done with an environment, you may deactivate it.

For this class, we want to have a bit more control on the packages that will be installed with the environment so we will create an environment with a so-called YAML file called `install_gds_stack.yml` (you will find it later in this page). Originally YAML was said to mean *Yet Another Markup Language* referencing its purpose as a markup language with the yet another construct. Still, it was then repurposed as *YAML Ain't Markup Language* [source:wikipedia].

#### Creating an environment from an environment.yml file

- Open up a terminal ("Anaconda Command Prompt" in Windows, "Applications --> Utilities --> Terminal" in macOS and  "ctr+alt+T" in Linux) and run the following commands:
    - Get the installer file from {{% staticref "epa1316-2020/install_gds_stack.zip" "newtab" %}}here{{% /staticref %}} and unzip it.
    - Navigate to the folder where this file is (e.g. Downloads):

        ```shell
        cd /path/to/Downloads
        ```

    - Execute the following command (note you will need a good and stable internet connection and will take a while to complete):

        ```shell
        conda-env create -f install_gds_stack.yml
        ```

    - Once this has run, you should be able to activate the environment:

        ```shell
        conda activate gds
        ```

        You should see the name of the environment at the start of your command prompt in parenthesis.

    - Verify that the new environment was installed correctly:

        ```shell
        conda list
        ```

        This will give you a list of the packages installed in this environment. For reference, go to [Manage conda environments](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

    - It will take approximately 15 minutes to install all packages.

## 2) A comprehensive approach: the GDS Docker container

This option is the recommended approach if you meet the following requirements:

1. You have admin rights over your machine
1. You are running either Windows 10 Pro, macOS, or Linux

In that case, [Docker](https://www.docker.com/) is the preferred alternative. It provides a stable platform to run complex software setups like that required in this context. Docker is a containerisation technology that allows to run pre-packaged (containerised) software under controlled environments. Relying on Docker, the [`gds_env`](https://github.com/darribas/gds_env) project provides a containerised platform for Geographic Data Science.

The steps to install this (given you meet the requirements above) include:

- Obtain a copy of Docker and install it:
    - `Windows10 Pro/Enterprise`: [Install Docker Desktop for Windows](https://docs.docker.com/docker-for-windows/install/)
    - `macOS`: [Get started with Docker Desktop for Mac](https://docs.docker.com/docker-for-mac/)
- Once Docker is successfully installed, make sure to enable access to your main drive (e.g. `C:\\`):
    - `Linux Users`: Open the preferences for Docker and click the
      "Shared Drives" tab; click on the drive you want to add and then "Apply"
    - `Windows10 Pro/Enterprise and macOS`: this feature is automatically enabled but windows will ask you to give permission to access your drive (ex. ‘Do you want to share a file with C:/User ‘)
- Once you have Docker up and running, open up a (Docker) terminal:
    - `macOS`: Open `/Applications/Utilities/Terminal.app`
    - `Windows10 Pro/Enterprise`: Powershell

    Then, type on the terminal the following command and hit `Enter`:

    ```shell
    > docker pull darribas/gds_py:5.0
    ```

    This docker will take a while to download but, once finished; you will be all ready to go.

- Once the command above has finished installing your GDS stack, you are ready to go! To get a Jupyter session started, you can follow these steps:
    1. Run on the same terminal as above the following command:

        ```shell
        > docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds_py:5.0
        ```

    This command will start a Python session; please do not quit the terminal window until you are
    done using Python!

    2. Open your favourite browser (preferably Firefox or Chrome) and point it to
       `localhost:8888`
    3. You will be asked for a password or a token. To find the correct one, check
       the terminal where you started the `docker run ...` command in 1) and look
       for the long token in the logs. Your prompt should look something (albeit
       not exactly) like this:

       ```shell
        > docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds:3.0
        Executing the command: jupyter notebook
        [I 11:38:40.234 NotebookApp] Writing notebook server cookie secret to /home/jovyan/.local/share/jupyter/runtime/notebook_cookie_secret
        [I 11:38:41.328 NotebookApp] Loading IPython parallel extension
        [I 11:38:41.612 NotebookApp] JupyterLab extension loaded from /opt/conda/lib/python3.8/site-packages/jupyterlab
        [I 11:38:41.612 NotebookApp] JupyterLab application directory is /opt/conda/share/jupyter/lab
        [I 11:38:43.091 NotebookApp] Serving notebooks from local directory: /home/jovyan
        [I 11:38:43.091 NotebookApp] The Jupyter Notebook is running at:
        [I 11:38:43.091 NotebookApp] http://ee20e7549b49:8888/?token=4dc814ee44c64383d5d32dfd439fe62bbc17d9803d9ae434
        [I 11:38:43.091 NotebookApp]  or http://127.0.0.1:8888/?token=4dc814ee44c64383d5d32dfd439fe62bbc17d9803d9ae434
        [I 11:38:43.091 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
        [C 11:38:43.114 NotebookApp]

            To access the notebook, open this file in a browser:
                file:///home/jovyan/.local/share/jupyter/runtime/nbserver-6-open.html
            Or copy and paste one of these URLs:
                http://ee20e7549b49:8888/?token=4dc814ee44c64383d5d32dfd439fe62bbc17d9803d9ae434
             or http://127.0.0.1:8888/?token=4dc814ee44c64383d5d32dfd439fe62bbc17d9803d9ae434
       ```

       The token you want to copy is the long series of letter and numbers right
       after `?token=`, starting by `4dc814ee`.
    4. The token should let you into your Jupyter Lab session. Congratulations!
       You can then access the files in your computer through the `work` directory
       on the left-side panel.
