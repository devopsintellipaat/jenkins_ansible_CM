<br>#Jenkins Ansible Docker Kubernetes </br>
<br>Install tomcat on worker machine.</br>
----------------------------------------------
<br>apt-cache search tomcat &&</br>
<br>apt-get install tomcat9 tomcat9-admin &&</br>
<br>systemctl enable tomcat9 &&</br>
<br>ufw allow from any to any port 8080 proto tcp</br>
----------------------------------------------

