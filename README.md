# tmux-configs
My tmux configuration files
The file named "remux" should be place in the users ~/bin/ directory, and set as executible.

"tmux.conf" is the custom local config for the local system.
if global to all users on a system the file will be found:
	/etc/tmux.conf

The user specific configuration file should be placed in the users home directory, like below:
	~/.tmux.conf
  
Inside of the user's specific .tmux.conf file will need to be modified for whether it is going to be used for a tmux v2.8 (and earlier) installation, or for a tmux v2.9 (or later) installation.
