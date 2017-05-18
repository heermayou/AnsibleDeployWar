# AnsibleDeployWar
Deploy war or zip to Tomcat/Dubbo
写这个脚步的目的是因为，github上，ansible部署java应用的方案，都是把tomcat做成服务，通过service tomcat stop 控制
然而，现在公司基本没这么做，基本通过shutdown.sh，停应用，不行，再kill
所以，改写了这个脚步
