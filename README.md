# FULL-WORKING-SQL-PHPMYADMIN-ANDROID-XAMPP

## Setup
## Steps for WINDOWS ON XAMPP
  - Git clone this Repository
  - Copy android_login folder to XAMPP=>htdocs
  - Change Config.php file for username and password
      
      $username = "root"; 
      $password = "pass"; 
      $host = "localhost"; 
      $dbname = "android_login"; 
  - Change Main Url inside Functions.Java File 
  - If you are using localhost:[PORT] change Mainurl to MAIN_URL = "http://10.0.2.2:[PORT]/android_login/"
  - If you are using just localhost change Mainurl to MAIN_URL = "http://10.0.2.2/android_login/"
