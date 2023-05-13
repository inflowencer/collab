Welcome to inflowencer's collaboration manual
=============================================

This guide contains instructions on how to efficiently collaborate, manage projects and work both scientifically and
practically on exchanging information.

.. note::

   This project is in ``Beta phase``.

Requirements
------------

+-------------------------+----------------------------------------------+-------------------------------------------------------+
| Step                    | Note                                         | Link                                                  |
+=========================+==============================================+=======================================================+
| Install WSL2 (Ubuntu)   | This step is only required for Windows users | https://learn.microsoft.com/en-us/windows/wsl/install |
+-------------------------+----------------------------------------------+-------------------------------------------------------+
| Install Visual Code     | IDE & source control                         | https://code.visualstudio.com                         |
+-------------------------+----------------------------------------------+-------------------------------------------------------+
| Install docker desktop  | Light-weight virtual machine                 | https://www.docker.com/products/docker-desktop/       |
+-------------------------+----------------------------------------------+-------------------------------------------------------+
| Create a GitHub account | For GitHub and Gitlab                        | https://github.com                                    |
+-------------------------+----------------------------------------------+-------------------------------------------------------+



Now you're reaady to collaborate. To access the repositories for collaboration, you have to:

1. Login to Github and create a `personal access token <https://docs.github.com/en/enterprise-server@3.4/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token>`_. Be sure to save it somewhere save.
2. Login to https://gitlab.com and create a `personal access token <https://docs.gitlab.com/ee/user/profile/personal_access_tokens.html#create-a-personal-access-token>`_. Be sure to save it somewhere save.
3. Send your **GitHub** and **Gitlab usernames** to inflowencer so he can add you to the repositories and give you required access rights.
4. Install ``glab`` for your terminal and login: 

   ..  code-block:: sh

      cd ~
      mkdir -p Downloads && cd Downloads
      wget https://gitlab.com/gitlab-org/cli/-/releases/v1.29.2/downloads/glab_1.29.2_Linux_x86_64.deb
      sudo apt install ./glab_1.29.2_Linux_x86_64.deb
      # Login
      glab auth login # use gitlab.com, your gitlab username and personal access token to login

Now you're set to clone, pull and push to repositories inside Gitlab and GitHub. Yay!

Contents
--------

.. toctree::

   usage
   api
