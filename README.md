# StudentProject

Setup

Tomcat server

download java [1.8]
# yum install java-1.8*

installation of tomcat
- download tomcat file 
	tomcat official site --> tomcat 8 --> zip file link copy --> on terminal download
# wget https://dlcdn.apache.org/tomcat/tomcat-8/v8.5.93/bin/apache-tomcat-8.5.93.zip

	unnzip the file
# unzip apache-tomcat-8.5.93.zip
# cd apache-tomcat-8.5.93

for tomcat start 
# cd bin
make sh file executable (permission)
# chmod +x *.sh

tomcat start stop command
# ./catalina.sh stop
# ./catalina.sh start

setup student application

# yum install git -y
# cd 
# git clone https://github.com/shubhamborkar25/StudentProject.git

# cd apache-tomcat-8.5.93/bin
# ./catalina.sh stop
# cp StudentProject/student.war apache-tomcat-8.5.93/webapps/
# ./catalina.sh start



google hit
localhost:8080/student
or 
IP:8080/student
