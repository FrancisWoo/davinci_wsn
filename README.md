# davinci_wsn
wsn experimental code for DaVinci robot

Startup rviz with: 
`roslaunch dvrk_model wsn_psm_one_rviz.launch`

or for dual arms:
`roslaunch dvrk_model wsn_psm_both_rviz.launch`


start a joint-state publisher with:
`rosrun davinci_kinematics davinci_cart_traj_pub`


This will cause the gripper tip to sweep out a circular path while holding the gripper orientation constant.

Looks encouraging.  Demonstrated Cartesian-space trajectories in rviz--including dual-arm motions.
See libraries in davinci_kinematics for fw, ik and joint publishing.

Still need to find and install actual joint limits.
Need to test assumption that legal IK solutions are unique.


