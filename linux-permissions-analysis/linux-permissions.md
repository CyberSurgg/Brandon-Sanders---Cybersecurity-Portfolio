File permissions in Linux
Project description
[Describe what you accomplish through Linux commands.]

In my role as a security professional, I used Linux commands to examine and change file permissions to ensure that only authorized users had access. I also used commands to locate hidden files on the system. This helps improve security by ensuring only the appropriate users have access to sensitive data.

Check file and directory details
[Add content here.]

I used the ls -l command to view detailed information about files and directories in your current directory. This command displays file permissions, ownership, and other important details. Checking this information is important because it allows me to identify who has access to specific files and ensure that permissions are set correctly to prevent unauthorized access.
Describe the permissions string
[Add content here.]

The permissions string is a 10-character sequence that shows access rights for a file or directory. The first character indicates the file type (such as - for a file or d for a directory). The remaining characters are divided into three groups representing the owner, group, and others. Each group contains three permissions: r for read, w for write, and x for execute. Understanding this string is important in cybersecurity because it helps determine who can access or modify files and ensures permissions are set appropriately.
Change file permissions
[Add content here.]

To change file permissions, I used the chmod command. This command allows you to modify who can read, write, or execute a file. I used it to remove certain permissions to restrict access to specific files. This is important for security because it helps prevent unauthorized users from accessing or modifying sensitive data.
Change file permissions on a hidden file
[Add content here.]

To change permissions on a hidden file, I first used the ls -la command to display all files, including hidden ones. Hidden files begin with a period (.) and are not visible by default. After identifying the file, I used the chmod command to modify its permissions just like a regular file. This is important for security because hidden files can still contain sensitive data, and restricting access helps prevent unauthorized use.
Change directory permissions
[Add content here.]

I used the chmod command to change directory permissions. This controls who can access and modify the contents of a directory. For directories, r allows users to view the contents, w allows users to add or remove files, and x allows users to enter the directory. This is important for security because restricting these permissions helps prevent unauthorized users from accessing or modifying sensitive files.


Summary
[Add content here.]

In this lab, I learned how to examine and modify file and directory permissions using Linux commands. I also learned how permissions control who can access or modify files. This is important for security because properly managing permissions helps protect sensitive data and prevents unauthorized access within an organization.

