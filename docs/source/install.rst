.. _install:

############
Installation
############

Installing under VS Code
-------------------------

You will need two things for this extension (three for Windows users):

1. `VS Code <https://code.visualstudio.com/>`_
2. `Anaconda python <https://www.anaconda.com/products/individual>`_
3. Perl, for Windows users

First, `download and install VS Code <https://code.visualstudio.com>`_. The suggested way to install this VS Code extension is
from the VS Code marketplace. Simply open the Extensions tab (or press ``CTRL/CMD + SHIFT + X``) after opening VS Code and search 
for BioNetGen. `This package <https://marketplace.visualstudio.com/items?itemName=als251.bngl>`_ will show up, click install. If 
this step doesn't work, please make sure you have the `latest version <https://vscode-docs.readthedocs.io/en/stable/supporting/howtoupdate/>`_.

Next, you will need Python installed, and you need to have your terminal environment set correctly. We recommend 
`anaconda python <https://www.anaconda.com/products/individual>`_. `Download and install anaconda python <https://docs.anaconda.com/anaconda/install/index.html>`_.
During the installation, we recommend adding Anaconda to your PATH environment variable when given the option.
In VS Code, open a new terminal (``CTRL/CMD + ``` or under ``Terminal -> New Terminal``) and test if you have access to Python package manager ``pip`` (by running ``pip -h``, for example). 
If you don't, you need to setup your environment so that the terminal has access to ``pip``; this is OS dependent and there are various 
guides you can find online.

Windows users should also install Perl at this point if not already installed. You can use ``conda install -c conda-forge perl`` to do this.

Finally, open a ``.bngl`` file in VS Code; this should check if the extension is installed, and will automatically install it if not. Once complete, make sure it's installed correctly by
running ``bionetgen -h``. If this doesn't work, you can open the command palette (``CTRL/CMD + SHIFT + P``) and run the ``BNG setup`` command.
Alternatively, you can open a terminal and run the install command (``pip install bionetgen``) yourself.

Additional Setup Advice
=======================
You may need to specify which installation of Python that VS Code uses.
To do so, open the command palette (``CTRL/CMD + SHIFT + P``) and select the command ``Python: Select Interpreter``, which will allow you to make your selection.
