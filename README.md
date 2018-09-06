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

