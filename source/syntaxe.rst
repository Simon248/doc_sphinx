..    include:: <isonum.txt>

=================
Syntaxe
=================

https://sublime-and-sphinx-guide.readthedocs.io/en/latest/notes_warnings.html


Les titres
=================
.. code:: rst
    
    ====================
    Titre de niveau 1
    ====================

.. code:: rst

    Titre de niveau 2
    =================

.. code:: rst

    Titre de niveau 3
    -----------------

.. code:: rst

    Titre de niveau 4
    ~~~~~~~~~~~~~~~~~

.. code:: rst

    Titre de niveau 5
    ^^^^^^^^^^^^^^^^^

.. code:: rst
    
    Titre de niveau 6
    """"""""""""""""""

Les notes
=================

`.. note::`  

.. note:: 

    ceci est une note

`.. warning::`

.. warning:: 
    
    ceci est un warning

`.. attention::`

.. attention:: 
    
    ceci est une attentionceci est un rubric

`.. important::`

.. important:: 
    
    ceci est important

`.. tip::`

.. tip:: 
    
    ceci est un tip

`.. hint::`

.. hint:: 
    
    ceci est un hint

`.. seealso::`

.. seealso:: 
    
    ceci est un seealso

`.. admonition::`

.. admonition:: titre

    ceci est un admonition

`.. hlist::`
    

 .. hlist::
    :columns: 3
    
    * item 1
    * item 2
    * item 3

`.. list-table::`

.. list-table:: 
    :widths: 10 90 180
    :header-rows: 1

    * - Colonne 1
      - Colonne 2
      - Colonne 3
    * - Ligne 1
      - Ligne 1
      - Ligne 1
    * - Ligne 2
      - Ligne 2
      - Ligne 2

`.. csv-table::`

.. csv-table:: Table Title
   :file: CSV file path and name
   :widths: 30, 70
   :header-rows: 1

save a table as csv file and use the path to make your table in rst

Les tableaux
=================

.. code:: rst

    +-----------------+-----------------+
    |  Colonne 1      |  Colonne 2      |
    +=================+=================+
    |  Ligne 1        |  Ligne 1        |
    +-----------------+-----------------+
    |  Ligne 2        |  Ligne 2        |
    +-----------------+-----------------+

+-----------+-----------+
| Colonne 1 | Colonne 2 |
+===========+===========+
| Ligne 1   | Ligne 1   |
+-----------+-----------+
| Ligne 2   | Ligne 2   |
+-----------+-----------+



Le unicode
=================

add `..include:: <isonum.txt>` in the file to include unicode 

|rarr| |larr| |uarr| |darr|