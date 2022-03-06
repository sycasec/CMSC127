# File System vs DBMS

File systems and Databases are commonplace in the modern age of technology. Most people may not realize it, but there are file systems and databases everywhere, all within arms reach - in our mobile phones, tablets, and computer devices. 
<br/>
## File Systems

  A file system is designed to organize and store files - `.txt`, `.docx`, `.wav`, `.jpeg`, `.bmp` and many more into storage devices, allowing retrieval of data whenever the user wishes to. As such, the file system keeps files into directories, describes the **date created** and when it was **last modified**. In this way, the ***File System*** allows us to properly store and keep track of our music, photos, documents, and many more into whatever readable and writable storage we wish to use. The file system is usually directly installed into the computer with your Operating System. Modern file systems like `NTFS`, `ext4`, `APFS` 

### In short, a file system:
- Is a software that manages and organises files in a storage.
- Allows you to read and write files into your storage medium.
- Allows for storage of different types of encoding into your storage medium.
- Newer File Systems like `NTFS`, `ext4` and `APFS` allow for more security , allowing for file permissions and encryption, as well as creating a backup for files in case of accidental deletion.
- These file systems however, are limited in the sense that only a specific OS provides compatability to certain file systems.

<br/>

## Database Management Systems

 - A Database Management System is a collection of programs that enables users to create and maintain databases. Raw, typed data is stored into databases, eg: Full Name, Age, Address, Contact Number, email, and many more. These data are used by various entities like banks, schools, and governments. Database Management Systems allows a user to perform various operations on these data, like creating, reading, updating, and deleting data within the database.

 - DBMS allows for the configuration of access policies and restrictions imposed on databases. For example, a database administrator may limit access to certain data stored within the database, and may restrict user actions and manage users.

- DBMS allows for creating backups and snapshots of the database, and some may provide recovery tools necessary to restore databases to their previous state effortlessly.

### In short, a database management system:
- Is a convenient way to control and modify access to data within the database
- Allows users to perform operations on a database: `creating`, `reading`, `updating`, and `deleting` data or entire databases.
- Allows for creating backups of the database
<br/> <br/><br/><br/>

## All in all, there really isn't much of a difference. What's the big deal?

- Databases are generally used for storing related, structured data, with well defined data formats. They allow for efficient insert, update and retrieval when you have thousands of rows and columns of data by the use of DBMS's like MySQL, PostgreSQL, and many more. Emphasis on ***RELATED***, databases are used for ***related*** data like the information on your bank account, your profile in the National Statistics Office, your School Profile, etc. These are usually built on top of existing File Systems.

- File Systems are structured around storing arbitrary and unrelated data, having faster read and write speeds and are already packaged into your Operating System. When you're just storing some files into your computer and you want to create multiple directories to store some of your text documents and mp3s, you dont really need to get your hands wet with some structured query language.


## In the end, storing data is storing data. Aren't they pretty much the same?
- They actually are! These days, file systems have been improved in such a way that they offer similar services such as data protection, and keeping recovery data in case of data loss. Query processing is also used in some file systems to increase speed. The clearest difference is that DBMS allows for a multi-user access and most file systems are tailored for single users only, and that most DBMSs are used for storing ***related data***. 
- **TL, DR:**
    - DBMSs are used for transactions and storing related data and are curtailed towards multi-user access, 
    - File Systems are focused on reading and writing data to a storage device and curtailed towards personal use. 


## sources!
    https://www.interviewbit.com/blog/file-system-vs-dbms/#:~:text=File%20System%20vs%20DBMS%3A%20Full%20Difference,-File%20System&text=A%20file%20system%20is%20a,%2C%20create%2C%20and%20manage%20databases.
    https://www.geeksforgeeks.org/difference-between-file-system-and-dbms/
    https://www.guru99.com/difference-between-file-system-and-dbms.html
    https://www.bmc.com/blogs/dbms-database-management-systems/
    https://www.youtube.com/watch?v=6Iu45VZGQDk - Neso Academy Database Management Systems
    https://www.youtube.com/watch?v=KN8YgJnShPM - Files & File Systems: Crash Course Computer Science #20
    https://stackoverflow.com/questions/38120895/database-vs-file-system-storage
    https://www.quora.com/What-is-the-difference-between-a-file-system-and-a-database/answer/Christian-Smith-2
<br/><br/><br/><br/><br/>

#### disclaimer
- this is fo scoo
- i have no idea what im talking about
- dbs are for storing raw unprocessed data like your mom's credit card number, the expiration date, and the 3 digits in the back lmao

- file systems are obviously your file system you bozo did i really have to talk about this in length?