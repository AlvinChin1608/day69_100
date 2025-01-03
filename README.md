# day69_100 
-------
# Blog Application with Flask
A simple blog application built with Flask that allows users to register, log in, and interact with blog posts. Admins can create, edit, and delete posts, while regular users can comment.

## Key Features:
- __Admin Privileges:__ Only admin users can create, edit, and delete posts.
- __User Interaction:__ Regular users can comment on posts.
- __Route Protection:__ Routes for creating, editing, and deleting posts are protected, ensuring only admins can access them and preventing privilege escalation via URL manipulation.
- __Database Integration:__ Uses SQLite and SQLAlchemy for data storage.
  
## What I Learned:
- Built a blog app using Flask and SQLAlchemy.
- Implemented user authentication and role-based access (admins vs. regular users).
- Applied best practices for form validation and password hashing.

### Admin privileges 
Create, Edit and Delete posts
![](https://github.com/AlvinChin1608/day69_100/blob/main/Admin_privileges-ezgif.com-video-to-gif-converter.gif)

### Non-Admin users
Only able to comment on posts
![](https://github.com/AlvinChin1608/day69_100/blob/main/ScreenRecording2024-12-31at19.28.05-ezgif.com-video-to-gif-converter%20(1).gif)
