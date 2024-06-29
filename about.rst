FSS plugin for Brainstorm
=========================

Generality
----------

This process uses the `Simulated Annealing Algorithm <https://it.mathworks.com/help/gads/what-is-simulated-annealing.html>`_
to apply the Functional Source Separation to a dataset, extracting the functional source S1 or M1 (one at a time).

Dataset description
-------------------

The dataset consists of:

* one subject, two acquisition runs (left and right stimulation) of about 4 minutes each
* sampling frequency of 5000 Hz
* subject stimulated by galvanic median nerve stimulation
* 63 acquisition channels

Plugin installation
-------------------

To install the FSS plugin, just save the **process_fss.m** file into **user_folder/.brainstorm/process/**
where **user_folder** stands for your Brainstorm installation folder.
This will make the process available in the pipeline editor menus,
when you use the Process1 or Process2 tabs.
Avoid using capital letters, spaces or special characters in the process file name.
`Further info here <https://neuroimage.usc.edu/brainstorm/Tutorials/TutUserProcess>`_