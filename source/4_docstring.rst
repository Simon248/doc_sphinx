..    include:: <isonum.txt>

=====================
Doc from DocString
=====================


Conf.py
=================


.. code:: python

    extension ={
    'sphinx.ext.autodoc',
    'sphinx.ext.napoleon'
    }

.. code:: python

    napoleon_google_docstring = True

.. code:: python

    napoleon_numpy_docstring = False

generate rst template
======================

.. code:: bash

    sphinx-apidoc -o path-to-your-code/ path-where-you-want-your-rst-to-be/


.. note:: 
    only needed after module creation.


Manage dependancies
======================

you can use :guilabel:`Mockup`

in the conf.py :

.. code:: python

    autodock_mock_importq = ['numpy', 'pandas']


Write docstring
======================

google format:

.. code:: python

    def function(arg1, arg2):
        """Summary line.

        Extended description of function.

        Args:
            arg1 (int): Description of arg1
            arg2 (str): Description of arg2

        Returns:
            bool: Description of return value

        """

 
| you can use todo in doc strings:
| .. todo::
|    - [ ] todo 1
|    
| you need to set in conf.py

 .. code:: python

   extension ={'sphinx.ext.todo'}
   todo_include_todos = True