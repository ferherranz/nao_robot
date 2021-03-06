^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package nao_bringup
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.5.3 (2014-12-14)
------------------
* add bottom camera to nao_full.launch
* Contributors: Kanae Kochigami

0.5.2 (2014-12-04)
------------------
* remove trailing spaces
* Added naoqi_sensors dependency
* deleted extra space
* added nao_ip and nao_port as args to work
* Add microphone launcher in nao_full
* Contributors: Arguedas Mikael, Mikael ARGUEDAS, kochigami, sambrose

0.5.1 (2014-11-13)
------------------
* bugfix: fixing python imports for nao_robot
* bugfix: python imports
* Contributors: Karsten Knese

0.5.0 (2014-11-06)
------------------
* update on rviz config
* moved pose manager into nao_robot
* transfer nao_robot
* 0.4.1
* update changelogs
* get the accent right in Séverin's name
* 0.4.0
* update changelogs
* update nao_bringup launchfiles to use new urdf
* 0.3.0
* update changelogs
* update maintainers
  Armin, thank you for all your work, in ROS, Octomap and NAO.
  Good luck out of the university !
* "0.2.3"
* Changelogs
* {ahornung->ros-nao}
* {ahornung->ros-nao}
* Add missing nao_sim.launch to nao_bringup install
* "0.2.2"
* changelog
* Replace accented character in package.xml files, seems to cause
  problems with bloom
* "0.2.1"
* Changelogs
* "0.2.0"
* Adjust version number mismatch
* Adding (edited) catkin-generated changelogs
* Adding bugtracker and repo URLs to package manifests
* nao_bringup: include nao_description launch files
* Adding force_python parameter to nao_driver.launch to switch
  between C++ and python nodes for nao_sensors (Issue `#11 <https://github.com/ros-naoqi/nao_robot/issues/11>`_)
  Parameter will be passed on from higher-level launch files (nao_bringup).
  Default node is C++, unless a simulation launch file is started.
* Add nao_sim launch file to bringup simulated nao
* [nao_bringup] Include pose_manager in nao.launch
* Include nao_driver/launch/nao_driver.launch instead of copying its content
* XML comments do not work well in launch files...
* Added nao_bringup: provide general launch file for ROS on Nao
* Contributors: Armin Hornung, Karsten Knese, Séverin Lemaignan, Vincent Rabaud, margueda
