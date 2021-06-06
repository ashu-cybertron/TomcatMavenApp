# TomcatMavenApp
Sample Tomcat Maven App
# TomcatMavenApp by ashutosh kumar sah 
## here we integrate and create a pipeline 
### then master jenkins will run a docker container inside that container jenkins and tomcat will bw running for this maven app you just not need to worry
##docker run -itd -p 8025:8080 -p 8036:8036 --name my_tom_server ashucybertron/task3:latest
##docker exec -itd my_tom_server bash
###run these two commands and goto jenkins and change the Ip in the post build action and this app will be running for u 
