Preparing the directories and copying the data
=====

Create directories
------

First, let's create the new directory ``dataset`` in your ``home`` folder. 

.. code-block:: console

   mkdir dataset


And create the other directories and subdirectories that you will need for this session: 

.. code-block:: console

   mkdir reads_qc
   mkdir denovo_assembly
   mkdir denovo_assembly/qc
   

Define variables for convenience:

.. code-block:: console

   DATA=~/dataset
   DENOVO=~/denovo_assembly
   
   
   
Copy the data
-----

Now, copy the data into our data directory:

.. code-block:: console

   cp -r /media/ext1tb/share/2021_imbb_genomics_workshop_data $DATA
   
 
  
