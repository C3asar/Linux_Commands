## Give permission to folder and subfolder
>$ sudo chmod a+rwx /var/szDirectoryName
* __Where szDirectoryName is the name of the directory you would like, a means "all" (users) + means "add the following rights" and rwx means read, write and execute respectively...__

##To start, restart, stop XAMPP
>$ sudo /opt/lampp/lampp start/stop/restart

##Stop Mysql / Arch disto
>$ sudo systemctl stop mysql

##Find and kill and open port
>$ sudo netstat -nap | grep :443 || 80
>$ sudo kill {port}

##To write a text down using the command line
>$ echo 'Hello world' > index.php

##Show up what's inside the file
>$ cat index.php

##Deal with the conda env
	- Start the env
>$ conda activate
	- Stop the env
>$ conda deactivate
	- Start the project env
>$ source project/bin/activate\n



chrome://flags/#disable-webrtc-hw-decoding