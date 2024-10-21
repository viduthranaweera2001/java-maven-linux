# java-maven-linux

https://www.oracle.com/java/technologies/downloads/#java23


sudo dpkg -i <downloaded file>

sudo apt install -y libc6-i386 libc6-x32

sudo update-alternatives --install /usr/bin/java java /usr/lib/jvm/jdk-23/bin/java 1

sudo update-alternatives --install /usr/bin/javac javac /usr/lib/jvm/jdk-23/bin/javac 1


sudo gedit /etc/environment

JAVA_HOME="/usr/lib/jvm/jdk-23/"


source /etc/environment

echo $JAVA_HOME
