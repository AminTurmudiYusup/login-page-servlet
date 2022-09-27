# servlet-admin-lte
This Project describe how integrate admin lte login page with servlet and jsp
Prerequisite
1. You already familiar create maven web using Intellij Idea
2. You Understand mapping request in servlet using web.xml
3. You understand web server(especially jetty, because I'm using jetty in this tutorial)
4. You understand maven concept

What needed?
1. admin lte template(you can download from this github https://github.com/ColorlibHQ/AdminLTE)

Let's Jump right in
1. open intellij Idea and create maven project
2. change compiler to jdk 11
3. open pom.xml and add servlet and jstl dependency(after add dependency load pom.xml)
4. add jetty plugin
5. create package and servlet class
6. mapping servlet class on web.xml
7. and set url patern to empty string
8. set contextPath in pom.xml
9. try to run first, with this command ( mvn jetty:run)http://localhost:8080/myWebApp/
the next step is copy login page from bootstrap template
10. copy login page html from bootstrap into WEB-INF folder and rename extension to .jsp
11. create css folder and add css to css folder
12. create js folder and add js to js folder
13. add jstl core in jsp page(make sure you have jstl dependency and add jstl core into login page.jsp)
14. load css and js into jsp page
15. try to run using this command( mvn jetty:run)
16. change mapping after servlet run


Succeed, Happy Learning and Happy Sharing!!!

# HOW TO RUN
1. import project to intellij idea or other idea
2. run using maven command = mvn jetty:run
