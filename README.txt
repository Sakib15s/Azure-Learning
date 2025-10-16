Azure deploy jerkins on Azure VMS

1. created a resources group
1.create a VM ubuntu and with SSH 
2.vm created asked to dowanload the Key pair
3. downloaded Gitbash
4. connecting VM through gitbash with the public IP of the VM
5. Ubuntu is running conneted 
6. deploying Jenkins
7.  for that I pre- requeisted installed Java 
		sudo apt updated 
		Sudo apt install openjdk-11-jre
 	and checking the version 
		java -version
8. after that I am using this command ps -ef |grep Jenkins to see jenkinds running
9. created an add inbound security rule allowing 8080 for jerkins
10. searched http://http://40.82.192.255:8080
working Jenkins 
