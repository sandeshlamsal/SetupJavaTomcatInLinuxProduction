# SetupJavaTomcatInLinuxProduction

First install JDK
-----------------

# cd /opt/
# wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u91-b14/jdk-8u91-linux-x64.tar.gz"

# tar xzf jdk-8u91-linux-x64.tar.gz


set up path for jdk home
-----------------------
check the env varaibles with

# printenv


Install tomcat and Run 
----------------------

http://tecadmin.net/install-tomcat-8-on-centos-rhel-and-ubuntu/ 


run: startup.sh to run tomcat

http://ip:8080 to run

change the user login setting

<!-- user admin can access manager and admin section both -->
<role rolename="manager-gui" />
<user username="admin" password="admin" roles="manager-gui" />
