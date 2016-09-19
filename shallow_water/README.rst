Shallow water equations on an Arakawa C-grid
============================================

These examples use rpe_ to investigate the performance of a shallow water
equation model defined on an Arakawa C-grid. These model configurations are
described in Dawson and Düben (2016).

Model configurations
--------------------

Source code for the following model configurations is provided:

* ``sw_ref.f90``:

  A reference double-precision implementation

* ``sw_reduced.f90``:

  A version with a uniform reduced floating-point precision for all variables

* ``sw_codesigned.f90``:

  A co-designed half-precision version that uses half-precision for computing
  RHS terms and double-precision for time-stepping update operations

.. _rpe: http://github.com/aopp-pred/rpe
