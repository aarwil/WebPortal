**A Web Portal**

| Portal Name       | **Employee Management System** |
| --- | --- |
| Role        | Admin |
| Features        | Add, Edit, Delete, View, Bulk upload data and Upload picture |
| Software Language | MySQL, PHP, JavaScript and HTML |

**Introduction:**

- It is a sample web portal for beginners with login restriction.
- This portal is also responsive for all devices.
- Additional new feature is the bulk upload **data count** and find the duplicate data while uploading


**Login Page:**

- Only Admin can login using their Email ID and Password which is already created in the **Database** (predefined email id and password) **.**
- After the entering the email id and password click the login button to execute the MySQL query which is to check whether the given email id is available in Database are not.
- After successful login a session is created for the email id.

**View Detail Page:**

- The data fetched from the database which is shown in the view detail page is the data that created by an Admin.
- The Search box is used to search the details in the view detail page.
- The Show Entries are used to modify the required number of columns to be shown in the table view.
- The Edit and Delete options which are in action column is to update the data.
- The admin name will be displayed at the top right corner before the Logout button

**Register Form Page:**

- The form page is to create user details in the database.
- Since the Admin ID and Admin Name are set in session variable, after submitting the data entered in the form fields will store the data with the Admin ID in the database.
- Reset button is to reset the form fields.



**Bulk Upload Page:**

- The bulk upload section nly supports CSV files to upload the data in database.
- The Sample file format is available so that admin can upload the data in the database in a given format. The upload data should match the sample template which can be downloaded by clicking the download icon.
- An email is sent while uploading the data to employee mail id and admin mail id. If the uploading data is already registered in database (duplicate data), will sent a mail to notify the presence of duplicate data to the admin.



**Data inserted count:**

- **A new feature** which counts the number of data uploaded from the csv bulk upload.
- It also finds number of duplicate data and saves the duplicate data in a separate table

**Edit Section:**

- This section is to edit the details by clicking the edit icon in action column.
- The selected user details are fetched and inserted in the form fields
- After editing click the update button to update the details in database.

**Delete:**



- While clicking the delete icon, alert window will open to confirm whether the user really wish to delete the details.
- After confirmation, details will be soft deleted.
- Soft delete will actually change the status of the database. It won&#39;t affect or do any changes in the database.



**Dashboard Page:**

- Dashboard is still working under construction.
- Still under planning to add some new features to show something interesting.

**How To Start in a local server**

**Step1** : Download Xampp

- Download **xampp** or any **mysql** software as a database.(I used xampp)
- Install xampp and open the xampp controll panel.
- It will open a dialog box; there you will find **Actions** start buttons. Start the apache and mysql only.
- Then select the admin button it will open the local host php myadmin page in the default browser.

**Step2:** SQL upload(table creation)

- Create a database and give a name to the DataBase
- Upload the sample.sql file in the upload section.
- Now the admin tables are automatically created.
- You can change the user name and password in the admin table for your purpose.

**Step3:** Final Process

- Select all the files and folders, and make a copy of it.
- Now open the **xampp** folder where you have installed in the directory.
- Then find the **htdocs** folder and open. Then create a New folder and name it as your choice example: foldername
C/: xampp htdocs foldername

(Caution: Make sure you do not use capital letters and don&#39;t use space for the folder names).

- Now open the env.php file and make changes according to the database name, domain name/ folder name(you created), admin table name.
- The folder name you created is your domain name. Now open your browser and hit [http://localhost/foldername/](http://localhost/foldername/)
- After that, open the xampp control panel select the stop button in apache and mysql.(For closing the server).







**Congratulations!! That&#39;s your new web portal!!!**
