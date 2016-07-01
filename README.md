# comp1950project
COMP1950 Web Design and Development final project

To run this project on your web server
1. Make sure comp1950project folder is under your student folder
For example,
   D:/WAMP/htdocs/students/{your name}/comp1950project
   
2. Make sure the DocumentRoot is set to "htdocs"
For example,
   DocumentRoot "D:/WAMP/htdocs"
   
3. Make sure your .htaccess file cover .inc file extension

  AddType text/html .shtml .html .htm .inc
  AddHandler server-parsed .shtml .html .htm .inc
  Options Indexes FollowSymLinks Includes 
  
4. Edit site_config.inc file (found under comp1950project/inc/) to reflect your student name

  <!-- Variable to use across site -->
  <!--#set var="studentpath" value="/students/{your name}/" -->
  
5. Restart the server, you can access the homepage from

  http://localhost:port/students/{your name}/comp1950project/
