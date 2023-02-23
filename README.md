
# Quell Move 

QuellMove is dedicated to providing the most advanced and comprehensive software as service for the moving and storage industry. 

It is a mobile and cloud-based software solution which revolutionizes the way moving inventory is recorded and managed. On-site moving crew documents all items in a move faster, better and more economically way than pen and paper. Easy to use. Customers, crew and company management have an audit trail of all the items, at any time. No more lost items, everything is trackable from your mobile device or desktop.


## Framework

The project is built using VueJS as the front end framework and Laravel PHP as the backend database.

## Installation Tools & Files

**.env File**

The . env file contains the individual user environment variables that override the variables set in the /etc/environment file. You can customize your environment variables as desired by modifying your . env file.

**XAMPP Server**


XAMPP is a local server that you can install on your laptop/desktop to mimic an actual web server. It's a completely free, open source Apache server distribution with MariaDB (formerly MySQL), PHP, and Perl.

**npm**

npm stands for Node Package Manager. It's a library and registry for JavaScript software packages. npm also has command-line tools to help you install the different packages and manage their dependencies. npm is the default package manager for the JavaScript runtime environment Node.js.

**Composer** 

Composer is an application-level dependency manager for the PHP programming language that provides a standard format for managing dependencies of PHP software and required libraries.

**PHP ARTISAN**

It is the command line interface/tool included with Laravel. It provides a number of commands that can help you while you build your application easily. 

**NodeJS**

Node.js is an open source server environment.It allows you to run JavaScript on the server.
## Installation Steps

For the project setup, make sure all the installation tools and files are available and then run the below listed commands.

1) Add .env file to the root folder

2) Launch the Xaamp Server and open PHP MyAdmin panel. 

3) Add a database for the project.
   
   **Note**: The name of the database should match with the name in the .env file.

4) Open the terminal and run the commands listed below that help us to link database with the project using PHP ARTISAN and install relevant files/dependencies using npm.

- composer install 
The install command reads the composer.json file from the current directory, resolves the dependencies, and installs them into vendor 

- php artisan passport:install
This command will create the encryption keys needed to generate secure access tokens.

- npm install 
This command installs a package and any packages that it depends on.

- php artisan clear:all
This command  will clear all the cache data in storage.

- php artisan plan:sync
As the name suggests, this command synchronizes the database entries.

- php artisan optimize:clear 
This command clears all Laravel's cache data.

- php artisan config:cache
To give your application a speed boost, one  should cache all of your configuration files into a single file using this command. It will combine all of the configuration options for your application into a single file which can be quickly loaded by the framework.

- php artisan config:clear
It will remove all the cache associated with the connection to the database.

- npm run dev
When working on a website locally, you use this command to start the development server. It is used to run the dev script defined inside a package. json file. 

-(optional) Add mail login credentials i.e username, password, recovery password, email protocol in .env file.

-(optional) Add pusher credentials in .env file for availing Broadcast functionality.

- php artisan serve
This command helps running applications on the PHP development server. As a developer, one can use this command to develop and test various functions within the application.