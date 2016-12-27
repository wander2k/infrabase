# infrabase
Confirmed in windows 7
Using docker, build your own infra base for development with Gitlab / Redmine / Jenkins

Dependencies:
1. Git
2. Docker toolbox for windows

Usage:
1. Open docker quickstart terminal 
2. Git clone https://github.com/wander2k/infrabase.git
3. cd infrabase
4. docker-compose up -d
5. docker-machine ip
6. Edit C:\Windows\System32\drivers\etc\hosts with administrator permission:
       192.168.99.100	jenkins.mydev
       192.168.99.100	gitlab.mydev
       192.168.99.100	redmine.mydev
       ## 192.168.99.100 is confirmed in step 5
7. Open browser, access your tool:
   http://jenkins.mydev
   http://gitlab.mydev
   http://redmine.mydev  
   
   
