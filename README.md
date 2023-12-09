
PreRequisites :

1. Install NVIDIA Container Development toolkit
            following the instructions
 [here](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html).

2. Install following extensions on your VSCode: 

    [2.1 Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

    [2.2 Remote-Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

[DevContainer Reference](https://containers.dev/implementors/json_reference/#remoteUser)
Running a DevContainer in VScode :
Press ` Ctrl + Shft + P ' choose rebuild and reopen containers

Environment :

1. Ros2 Humble
2. Gazebo Garden

## Reuse
    
In the Docker file : go to line 168 and change to your desire workspace folder name(the folder name you cloned this repo to).
Open this folder in Vs code and press 'ctrl + Shft + B'. select rebuild and reopen in container.

## Setup Dependencies

once you are inside the DevContainer (see bottom left of VS code), press `ctrl + Shft + B` 
