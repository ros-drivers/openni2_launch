^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package openni2_launch
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.4 (2014-05-22)
------------------
* Force device_id to string type
* Contributors: Dariush Forouher

0.1.3 (2014-05-07)
------------------
* Add tf_prefix same as openni
* Fix issue `#9 <https://github.com/ros-drivers/openni2_launch/issues/9>`_
  This way the defaults for depth processing are set apropriately for both
  hardware and software registration.
* Contributors: Libor Wagner, Mark Pitchless, Michael Ferguson

0.1.2 (2013-09-30)
------------------
* Expose driver parameters. Note: depth_registration is now off by default.

0.1.1 (2013-09-25)
------------------
* Properly namespace the nodelet manager

0.1.0 (2013-09-10)
------------------
* First release
* This package is a thin wrapper around rgbd_launch
