`ClangCloneDetectionBear <https://github.com/coala-analyzer/coala-bears/tree/master/bears/c_languages/codeclone_detection/ClangCloneDetectionBear.py>`_
=======================================================================================================================================================

Checks the given code for similar functions that are probably redundant.

`Supported Languages <../README.rst>`_
--------------------------------------

* C
* C++
* CUDA
* Objective-C
* Objective-C++
* OpenCL
* OpenMP

Settings
--------

+---------------------------+--------------------------------------------------------+
| Setting                   |  Meaning                                               |
+===========================+========================================================+
|                           |                                                        |
| ``max_clone_difference``  | The maximum difference a clone should have. (Optional, |
|                           | defaults to '0.185'.)                                  |
|                           |                                                        |
+---------------------------+--------------------------------------------------------+


Dependencies
------------

* ``pip`` - ``libclang-py3``


Can Detect
----------

* Duplication