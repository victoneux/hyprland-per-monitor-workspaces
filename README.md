### Hyprland Per Monitor Workspaces

Allows you to have workspaces seperated by monitor.

### Configuration

bind=SUPER,1,exec,{script_path}/set_hyprland_workspace.sh 1

bind=SUPER,2,exec,{script_path}/set_hyprland_workspace.sh 2

bind=SUPER,3,exec,{script_path}/set_hyprland_workspace.sh 3

bind=SUPER,4,exec,{script_path}/set_hyprland_workspace.sh 4

...

bind=ALT,1,exec,{script_path}/move_hyprland_workspace.sh 1

bind=ALT,2,exec,{script_path}/move_hyprland_workspace.sh 2

bind=ALT,3,exec,{script_path}/move_hyprland_workspace.sh 3

bind=ALT,4,exec,{script_path}/move_hyprland_workspace.sh 4

...

exec-once={script_path}/hyprland_mon_socket.sh
