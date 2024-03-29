How to install ViLLM?
=====================

Installing Repo
---------------

Follow these steps to install Repo. The instructions are taken from the `official documentation <https://source.android.com/setup/develop#installing-repo>`_.

.. code-block:: bash

    # Make sure you have a bin/ directory in your home directory and that it is included in your path:
    mkdir ~/bin
    PATH=~/bin:$PATH
    # Download the Repo tool and ensure that it is executable:
    curl https://storage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

Cloning ViLLM
-------------

.. code-block:: bash

    # Create a directory for the ViLLM repository
    mkdir villm
    cd villm
    # Clone the ViLLM repository
    repo init -b main -u https://github.com/koyejo-lab/villm.git
    repo sync -j{number_of_threads}

Installing Dependencies
-----------------------

.. code-block:: bash

    # Install the required packages
    pip install -r requirements.txt