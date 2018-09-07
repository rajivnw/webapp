# webapp

git push --set-upstream origin master:dev1.0
git pull origin dev1.0

1.  List all tools
git
maven docker
kubetura....
cloud formation
email
-----------------------
2. Install the tools in machine
3. Configure the tool
4. make sure Jenkins user execude the tool
all users - usr/bin
Root user - usr/sbin
5. Install all plugins required 
  Restart Jenkin - A. Hard and B. Soft
6. configure all plugin 
7. use the plugin in the 

check service is running - sudo service jenkins status

------------------Docker-------------
sudo yum -y install docker
   
sudo service docker start
udo chkconfig docker on

docker build -t rajivnwli/myapache:1.0 .

docker tag  rajivnwli/myapach:1.0 rajivnwli/myapach:latest
docker tag rajivnwli/myapache:1.0 rajivnwli/myapache:latest
  
docker push rajivnwli/myapache:1.0
docker run -d -p 800:80 -v testmuapache_var_log:/var/log --name testmyapache rajivnwli/myapache:1.0

----------------------------Docker-------------------
sudo service docker start
docker build -t rajivnwli/myphp:1.0 .
docker tag  rajivnwli/myphp:1.0 rajivnwli/myphp:latest
docker push rajivnwli/myphp:1.0
docker run -d -p 800:80 -v testmyphp_var_log:/var/log --name testmyphp rajivnwli/myphp:1.0

--------------------------
docker run -dit ubuntu:18.04
docker exec -it blissful_booth /bin/bash
apt-get install

FROM ubuntu:18.04
MAINTAINER  RAJIV.NAWALI@GMAIL.COM

ENV TZ=America/Los_Angeles
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone

RUN apt-get update && apt-get install -y --no-install-recommends apt-utils
RUN apt-get install -y nginx
RUN apt-get install php -y
RUN apt-get install -y php-gd php-mysql
EXPOSE 80
ADD code /var/www/html
ENV BACKENDLB=test
CMD ["nginx", "-g", "daemon off;"]

https://drive.google.com/drive/u/0/folders/1zGjwkaR0nr9iqJcot7XBOyspzCf6VwP3

mohan@y2ytech.com

1. OS fundamentals
2. Shell scripts
3. All major platforms [Linux Project]
4. cloud - compute(VM,Docker,CAAS), Storage, netwrok databases,queqe, hadoop, iam,monitoring login
5. DevOps Tools - SCM,Build, Docker/VM, Deployent.
6. 4 archateture

web technology work flow
python work flow
Ruby
Hadoop
java
96110046506




