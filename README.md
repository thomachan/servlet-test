# tests
This is a simple servlet program, which write custom response header and an html also attached to check it wit an ajax on button click


Steps:

Deploy war file in tomcat with name servlet-test.war

request http://localhost:8080/servlet-test/testheader.html

click on Sign in button
Then alert will be shown value for 'AUTHORIZATION' custom header set from servlet
