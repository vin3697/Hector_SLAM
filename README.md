# Hector_SLAM


Doing Research on Hector SLAM, working to fine tune the parameters of move_base node.
Already the fellow team members have implemented it, but hardly it has been tuned to get the optimum results on our Ohmni Robot Buttler.
I have defined the parameters in the config folder, but still a lot of work has to be done in order to achieve optimum results as the DWA planner is not able to generate a path in local space, which forces the Robot to go in Recovery mode and this loop never ends, which stops the Navigation Stack.

For creating an environment map,**Hector SLAM** was used making necessary changes in the software launch files, taking cues from **RPLidar Hector SLAM** (https://github.com/NickL77/RPLidar_Hector_SLAM/tree/master).
