Tutorial Proposal for Scipy 2013
================================

:Tutorial Title: An Introduction to IPython and Numpy
:Track: Introduction Scientific Python Basics (Numpy and IPython)
:Author: Valentin Haenel
:Contact Email: valentin@haenel.co
:Version: 1.1
:Bio: Valentin Haenel is an software developer with experience working in a
      scientific context. He is the co-author of a scientific toolbox used in
      experimental psychology research and has worked on a large-scale brain
      simulation project in the past.

      He has been teaching at the `Advanced Scientific Programming in Python
      Summerschool materials <https://python.g-node.org/wiki/>`_ where his main
      focus is the lecture on best practices and contributing to the schools
      programming framework `Pelita <http://aspp.github.com/pelita/>`_. He has
      been tutorial chair for the `EuroScipy conference
      <https://www.euroscipy.org/>`_ in 2011 and 2012 and is one of the editors
      of the `Python Scientific Lecture Notes
      <http://scipy-lectures.github.com/>`_. Recently, he taught a `week-long
      course for PhD students and Postdocs at the EPFL in Switzerland
      <https://github.com/pcp13>`_ and authored an article about `interfacing
      Python and
      C <http://scipy-lectures.github.com/advanced/interfacing_with_c/interfacing_with_c.html>`_.

      See also: http://haenel.co
:Tutorial Description: This tutorial is a hands-on introduction to the two most
                       basic building-blocks of the scientific Python stack:
                       the enhanced interactive interpreter IPython and the
                       fast numerical container Numpy. Amongst other things you
                       will learn how to structure an interactive workflow for
                       scientific computing and how to create (or load) and
                       manipulate numerical data efficiently. You should have
                       some basic familiarity with Python (variables, loops,
                       functions) and basic command-line usage (executing
                       commands, using history).
:Outline: **Ipython** (1 hour)

          * Help system, magic functions, aliases and history
            (15 min lecture, 15 min exercises)
          * Using the IPython notebook
            (15 min demo, 15 min exercises)

          **Numpy** (3 hours)

          * Basic arrays, dtypes and numerical operations
            (30 min lecture, 30 min exercises)
          * Indexing, slicing, reshaping and broadcasting
            (30 min lecture, 30 min exercises)
          * Copies, views and fancy indexing
            (30 min lecture, 30 min exercises)

          During the exercises sessions, participants will be given exercises
          and solutions. I will walk around the room offering help and advice.

:Package List: An install of Anaconda should be enough

               * Numpy (Version 1.6 or higher)
               * Ipython (Version 0.13 or higher)
               * Matplotlib (Version 1.2.1 or higher)

:Documentation: I will use the corresponding sections from `Python Scientific Lecture
                Notes <http://scipy-lectures.github.com/>`_. There is quite alot of
                material there already. In preparation for this tutorial I would
                invest some more time to increase the coherence of the material
                and adding more short and easy exercises. Also, I will
                hopefully get the ``sphinx2ipynb`` converter to work properly such
                that I can give the lecture using an IPython notebook.
