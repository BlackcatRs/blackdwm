dwm pathes :

    dwm-status2d-6.3.diff

slstatus

dmenus



TODO :
     Increase font size
     Add padding bettween underline and tag icons
     Add eww
     Keybinding to some action like increse volume
     Create separate branche for patch launcher which is acctully in current branch



Xephyr -br -ac -noreset -screen 1680x1050 :1 &

DISPLAY=':1' $HOME/git/suckless/black-dwm-6.3/dwm &
make clean && make && DISPLAY=':1' $HOME/git/suckless/black-dwm-6.3/dwm

DISPLAY=':1' $HOME/git/chadwm/scripts/bar.sh &
