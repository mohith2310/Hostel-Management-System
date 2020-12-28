# Hostel Management System

A software that allows automation of currently existing hostel room allocation process,
while not compromising on the choices of the student's for their roommates and
hostels. 

## Installation

1. Firstly,install XAMPP software on PC.
2. Then open the XAMPP control panel and start apache and MySQL servers.
3. Open your web browser and go to http://localhost/phpmyadmin/
4. Create a new database with the name “hostel” by clicking the New on the left
panel on the PHPMyAdmin page and navigate to the hostel database where
you can find an import option.
5. Now unzip the dbms.zip file
6. There you can find hostel.sql, now import this hostel.sql into your hostel
database which you have created earlier
7. Now copy the paste the unzipped dbms folder into the htdocs folder in
XAMPP folder. This is the folder when you have installed your XAMPP app.
(You can probably find this folder in Windows C)
8. Since you have already started an apache server from the XAMPP control panel
directly, open the browser and go to http://localhost/dbms/pages/, this directly
brings up index.php from our files.
9. There you have an option to login as a student or else login as admin. If you want to login as a student you can register to this web-app by clicking “New
here? Create one” link which is located just above the login button.
10. You can also use credentials of pre-existing users which you can find in the
STUDENTS table of the hostel database.
11. To log in as admin you can use credentials of pre-existing admins in Admin
table of hostel database (or) you can the credentials of main admin which are:
Email: admin1@gmail.com Password: admin1
12. You can add new admins into the database when you login as the main admin.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
