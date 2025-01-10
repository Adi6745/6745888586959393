sudo su 
yum install git
mkdir vam
cd vam
git init
git config --global user.name "vam"
git config --global user.email "22r21a05d3@mlrit.ac.in"
git config --list
vi vamrepo
matter in file
to exit(:wq!)
git add .
git status
git commit -m "File is Created"
git status
git remote add origin "https://github.com/Vamshi2004-web/vamshi1.git"
git branch
git push -u origin master
username:'https://github.com': vam
password:
-----------------
sudo su
sudo yum update -y
sudo yum install docker -y

sudo systemctl start docker
sudo systemctl enable docker

docker --version
docker pull tensorflow/tensorflow 

docker images 
docker run -d -p 8080:8080 tensorflow/tensorflow

docker ps -a
----------
Jenkins


sudo su
sudo yum install java17 -y

past 2 commands that came in Jenkins 

sudo yum install jenkins -y

sudo systemctl start jenkins
sudo systemctl enable jenkins

now change security group
add rules of (custome)in inbound rules and save it

copy and past public ipv4 address :8080

more (give command there in in login page)

create git hub repo(add a java file)


open jenkiks link 
--------------
sudo su
wget https://dlcdn.apache.org/maven/maven-3/3.8.8/binaries/apache-maven-3.8.8-bin.tar.gz
tar -zxvf apache-maven-3.8.8-bin.tar.gz
ls
cd apache-maven-3.8.8
yum install java -y
yum install maven -y
java -version
mvn -version
mvn archetype:generate
batch
devops
Y
cd devops
(mvn compile)
ls target/
ls/target/classes/
mvn package
cd target
ls
---------4









