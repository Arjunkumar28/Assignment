1.I am currently doing Internship in Surfboard Payments to improve my knowledge and carrer path.
2.I am very happy to be a parth of Surfboard Payments and thank you for giving me wonderful opportunity.
3.On first day, I learnt how to log on to the linux and I learnt some commands like ls-list, cd-change directory, cp-copy, sudo-super user do.4.The operating system is the most significant fundamental of all the system programs, it controls all the computers resources and provides
  the base upon which the application programs can be written.
5.The Basic fundamental skills are
        * Reading
        * Writing
        * Mathematical thinking
        * Problem solving
        * Researching
        * Breakin down and synthesing
        * Typing
        * Creativity
6.ls-its used for list the file names and cd-its used for to enter into the file
7.mkdir-its used to create the directory and touch command used to create a file name
8.sudo command is used to get permission to admin
9.yum command will used for installing the appications in linux and instead of yum we can use apt-get command in the ubuntu.
10.wget command used for to install the browser in linux.
11.vi-vim this command is used for the text editor into the terminal.
12.In text editor we can able to use some commamd like ESC,insert,visual.
13.In text editor we can able save command and quit command, The commands are
       * :w it is used to save the file
       * :q it is used to quit the file
       * :wq this command is used to save and quit the file
       * u command is used for undo
       * ctrl+r command is used for redo
       * I- Insert command is used to type a text in a file
       * V- visual command is used to view the text file
       * Y command is used for copy a text
       * P command is used for paste a text
       * dd command is used to delete the entire line
       * shift+6 command is used to start of a line
       * shift+4 command is used to end of a line
       * G command is used to end a file
       * gg command is used to start a file
14.we can use arrow keys to move the cursor left, right,up,down otherwise we can use the command like
       * H command is used to move the cursor in left
       * J command is used to move the cursor in Down
       * K command is used to move the cursor in up
       * L command is used to move the cursor in right

15.git init command is used for track the dirctory and git is used for version control.
16.CLI- Command Line Interface is called as Terminal, after completion of CLI we should install the GUI-Graphical User Interface package.
17.Step to install the GUI package
       * Install Gnome GUI package using the YUM command in linux- "yum groupinstall "GNOME Desktop" "Graphical Administration Toll"
       * Enable GUI on the system startup in centos 7/RHEL 7 system uses targets instead of runlevel.
         'ln -sf /lib/systemd/system/runlevel5.target /etc/systemd/system/default.target'
       * finally we should reboot
18.GUI installation process in ubuntu
       * First step is to updated the apt package index and install tasksel. To do so execute the following Linux commands
        " sudo apt update"
        " sudo apt install tasksel"
       * Next, select the GUI you wish to install. Below table shows main desktop environments available for installation via tasksel
        " tasksel --list-tasks"
       * At this point you have selected GUI you wish to install and took a note of the relevant task name.
         Next, use tasksel command to install your selected GUI. For example to install the default Ubuntu GNOME desktop execute
        "sudo tasksel install ubuntu-desktop"
       * Reboot your system-"reboot"
       * At this point the GUI should start. You may need to select your desired desktop flavor on the login page before you login.
         In case the GUI is not starting at all, make sure your system boots into the graphical target. To do so execute
        "sudo systemctl set-default graphical.target"
19.Step to install the GUI package in ubuntu
       *  Login to your terminal and execute the following systemctl command to start GUI
         " sudo systemctl isolate graphical"
       * In case you wish to start the GUI automatically during the system boot change the boot target from multi-user to graphical
         "sudo systemctl set-default graphical.target"
20.System power off command is "telinit 0"
