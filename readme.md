## How to use?
1. Download and run tomcat.
2. Put example file in main folder of catalina 
![image](https://github.com/user-attachments/assets/28214c68-e5d6-4cdd-9ed5-9528eea9177b)
3. Build war: build-war.sh
```
% ./build-war.sh
### Create helloworld.war file

Calling jar

added manifest
adding: index.jsp(in = 98675) (out= 74186)(deflated 24%)
adding: WEB-INF/(in = 0) (out= 0)(stored 0%)
adding: WEB-INF/web.xml(in = 63) (out= 48)(deflated 23%)

Moving helloworld.war to dist/ with option --FORCE
mv: rename helloworld.war to dist/: No such file or directory

Done
```
4. Copy war to webapps:
```
cp helloworld.war ../apache-tomcat-11.0.1/webapps/
```
5. http://localhost:8080/helloworld/

![image](https://github.com/user-attachments/assets/0e80c511-5c91-4546-acbc-543357870fc7)

   
