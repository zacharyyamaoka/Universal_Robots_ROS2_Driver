
I don't want to use rosdep to avoid getting random dependecies. 
`ur_client_library` is needed though, let me try to install via sudo apt

`sudo apt install ros-jazzy-ur-client-library ros-jazzy-ur-msgs`

You cannot use COLCON_IGNORE as thoose packages are depencies


- It's great looking through the UR code to get inspiration from others. UR is the gold standard IMO. I like how they have a family of arms, it's what I aspire to as well.

Wow, so it turns out it's basically doing the exactly same things as my package! Likely cause I copy pasted from Denis Stogl :3

It means I don't actually need to even integrate it really? how to add gripper? Ok I guess I can make a custom URDF type thing at some point...
Definetly these are the basic ideas here though.