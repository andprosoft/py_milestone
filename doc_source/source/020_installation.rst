Installation
############

Installation from pip
+++++++++++++++++++++

The easiest instalation routine is by using pip.

Open an Anaconda Prompt (Start --> Anaconda 3 --> Anaconda Prompt) and
load the desired environment:

.. code-block:: console

    conda activate env_name
    
Replace ``env_name`` with the name of the desired environment. Now, pymilestone
can be installed:

.. code-block:: console

    pip install pymilestone

This will install pymilestone. It can now be imported in the following
way:

.. code-block:: python

    from pymilestone import Milestoneplan, Task, Milestone, Caption, Subcaption, Category
    
    # ...



Installation from Source
++++++++++++++++++++++++

To install py_milestone from source, first download the entire source.
In the example, the directory will be saved in ``D:\py_milestone``.
You must adjust the commands to your respective download location.

Open an Anaconda Prompt (Start --> Anaconda 3 --> Anaconda Prompt) and
load the desired environment:

.. code-block:: console

    conda activate env_name
    
Replace ``env_name`` with the name of the desired environment. Before 
running the installation command, change to the ``pymilestone`` directory:

.. code-block:: console

    D:
    cd pymilestone

Now, enter the following command:

.. code-block:: console

    python setup.py install
    
This will install pymilestone. It can now be imported in the following
way:

.. code-block:: python

    from pymilestone import Milestoneplan, Task, Milestone, Caption, Subcaption, Category
    
    # ...
    
  
Usage without Installation
++++++++++++++++++++++++++

You can also use py_milestone without installation. For this,
add the following lines to your Python script (before importing modules
from py_milestone).

.. code-block:: python

    import site
    site.addsitedir('D:\pymilestone\python')
    
    from pymilestone import Milestoneplan, Task, Milestone, Caption, Subcaption, Category
    
    # ...
    
Adjust the path to the ``pymilestone\python`` directory in the ``site.addssitedir()``
command.


    
