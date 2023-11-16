[Back to Portfolio](./)

Prometheus Website
===============

-   **Class: CSCI 434 - Human-Computer Interaction** 
-   **Grade: 100%** 
-   **Language(s): Java** 
-   **Source Code Repository:** [CSCI 434 - Human-Computer Interaction](https://github.com/RicoNoSuave/CSCI434-Human_Computer_Interaction)  
    (Please [email me](mailto:Ricardo.E.Harris@gmail.com?subject=GitHub%20Access) to request access.)

## Project description

This is a full-stack web application project utilizing React, Node.js, and Express.js to build a Forum for a possible senior project. Through this web application you can see recent updates on the project, download distributions of the project, and participate in forum-based discussions about the project through the creation and maintenance of a personal account.

## How to compile and run the program

To compile and run this project, you must have npm installed on your device, as well as nodemon. If you have a stable full-stack environment, then open two terminals and type the following commands:

```bash
cd server;
npm start;
```

```bash
cd client;
npm start;
```

## UI Design

As a Forum application, the first thing you should do is log in as the administrator (see Fig 1). After logging in as the administrator, the navigation bar will load the "Account" and "Management" buttons. Navigate to the Management page to create moderator accounts, delete users, and create updates on the project to display to visitors (see Fig 2). Afterwards, until you shut down the server, you can view updates in the update page regardless of login status (see Fig 3). You can also go to the "Download" page to download test text files from links for operating systems (see Fig 4).

To continue demonstration, I would recommend logging out as the administrator, then creating your own account (see Fig 5). The application will then take you to the Forum page. You can navigate to the Account page to edit any details about your account (see Fig 6). Alternatively, you can stay on the Forum page to create and view threads (see Fig 7). If you wish to comment on a thread, just click on the thread to bring up the thread page (see Fig 8). On the forum, you can see how many comments there are, as well as how many likes (see Fig 9).

![screenshot](/images/Prometheus_Site/Login_Admin.jpg)  
Fig 1. The login screen with admin credentials (admin@admin.com, password).

![screenshot](/images/Prometheus_Site/Management.jpg)  
Fig 2. The Management page.

![screenshot](/images/Prometheus_Site/New_Update.jpg)  
Fig 3. Loaded update.

![screenshot](/images/Prometheus_Site/Download.jpg)  
Fig 4. The Download page.

![screenshot](/images/Prometheus_Site/New_User.jpg)  
Fig 5. Registration example.

![screenshot](/images/Prometheus_Site/Account.jpg)  
Fig 6. The Account page.

![screenshot](/images/Prometheus_Site/New_Thread.jpg)  
Fig 7. Forum to create and view Threads.

![screenshot](/images/Prometheus_Site/Reply.jpg)  
Fig 8. Reply to a thread.

![screenshot](/images/Prometheus_Site/Post_Reply.jpg)  
Fig 9. Display after commenting and liking.

## 3. Additional Considerations

Note that npm distributions can be fickle. If the application does not run on your device, you may be required to create your own project environment. If so, you must copy ```clients/src/*``` into your own client directory, and ```server/*``` into your own server directory.

[Back to Portfolio](./)
