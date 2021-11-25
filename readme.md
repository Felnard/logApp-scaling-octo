# logApp-scaling-octo

During this pandemic, we usually encounter logbooks in malls, stores, schools, almost every where. Under Republic Act 11469, Bayanihan to Heal as One Act requires us to provide truthful information. The **logApp** is a sample application that logs the individual's personal information and the date and time he/she visits the place. To protect an individual's personal information (RA 10173, Data Privacy Act of 2012), only users with an admin account can view the list of individuals who visited the premises.

---

# Log App Design

![Admin Login](https://user-images.githubusercontent.com/56058005/143451142-acf5fccb-a077-4065-845f-fa1e2b17d3a9.png)
![Registration Form](https://user-images.githubusercontent.com/56058005/143454387-50cbd4a8-5c7c-4559-9966-ed9d7ed00e5c.png)
![List](https://user-images.githubusercontent.com/56058005/143506588-a4c563e4-b4f3-4a7c-898b-de63ef62f92e.png)

---

# Preparation of database

## Softwares you need

- XAMPP

  If you haven't install XAMPP yet, just click [here](https://www.pipeten.com/support/applications/how-to-install-your-own-phpmyadmin/) for the guide.

- Visual Studio Code or other code editor

### Clone my repository

1. Copy and paste this on your cmd. git clone (name of my repository)
2. Then move the file here (C:\xampp\htdocs) to run for our XAMPP but it may vary depending where you install your XAMPP

### Run XAMPP

1. You can see that there are many modules on the left side click the start button for the Apache and MySQL Module.
2. Open this [link](http://localhost/phpmyadmin/index.php) to access phpmyadmin.Click [here](https://www.phpmyadmin.net/) for more details about phpmyadmin
3. Create 2 tables in phpmyadmin

- PERSON - id, lastName, firstName, address, createdAt
- USERACCOUNT - id, username, password

### Set up Database Connection

1. Go to the config folder and open the config.php file
2. Edit the config file and put your XAMPP password and username and the name of your database.

   define('ROOT_URL', '');
   define('DB_HOST', 'Localhost');
   define('DB_USER', '');
   define('DB_PASS', '');
   define('DB_NAME', '');

   ***

# Author

## Felnard Suropia

  <img src="https://user-images.githubusercontent.com/56058005/143506180-59b54416-9aef-4919-9dc9-d21169bad07f.png" width="200">

**_Thank you to those who have contributed to this project and make it possible_**
