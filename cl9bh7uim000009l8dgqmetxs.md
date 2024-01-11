---
title: "Amplication"
seoTitle: "Amplication : A platform for... !?"
seoDescription: "What is amplication ?"
datePublished: Sun Oct 16 2022 15:02:14 GMT+0000 (Coordinated Universal Time)
cuid: cl9bh7uim000009l8dgqmetxs
slug: amplication
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1665923228386/g8IpV3eOH.png
tags: development, opensource, nodejs, blogswithcc, hacktoberfest2022

---

# ⛩Welcome Everyone⛩

In this Hacktoberfest 2022 I've been contributed to so many projects, One of them is Amplication.

## What is Amplication ❗❓

Amplication is an open‑source development tool. It helps professional Node.js developers to develop quality Node.js applications without spending time on repetitive coding tasks.

Amplication auto-generates fully functional apps based on TypeScript and Node.js.


❗❕Oh yeah I get this thing from [official documentation](https://docs.amplication.com/docs/)😅 so check that out also...

Here what you can actually do with amplication:


🔵 Easily create data models 📈, and role-based access control 📋 and let Amplication generate your application 📲.<br>
🔵 Instantly download the source code of your application or push a new Pull Request to a GitHub repository.<br>
🔵 Keep developing your application with your coding skills and come back to Amplication at any time to add models and roles and generate new versions ♻.<br>
🔵 Optionally, download or build a Docker container with your database 🗃, a Node.js application, and a React client and continuously deploy your application to the cloud ☁ or your local environment 🌝⛱.<br>

## 🤔How to Use? -> 😁Easy to Use!
Working in Amplication is so easy you can even start it with few steps:
### Step 1 - Create a New Service
1 . Sign-in to app.amplication.com.<br>
You should land on the New Service page. If you're not on the New Service page, click the Amplication logo in the top-left corner to reach the Projects page.<br>
![Screenshot (168).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665925474335/4BzfUgqYH.png align="left")
2 . Click the New Resource button, and then click on Service.<br>
![Screenshot (169).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665925492604/V7h-DErDZ.png align="left")
3 . In the New Service page, leave the default selections to create an empty service.<br>
4 . Click the Create Service button.

![Screenshot (170).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665925530910/bshQCFamE.png align="left")

The Overview window opens.


![Screenshot (172).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665925804210/cs7DB0Z79.png align="left")

### Step 2 - Create an Entity

1 . On the Overview page, click Go to Entities, or from the main menu (left sidebar) click the Entities icon. The Entities page opens. Here you see all the entities in your service.<br><br>
Click the Entities icon on the main menu (left sidebar) to reach the Entities page. Here you see all the entities in your application.


![Screenshot (173).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665926093756/JSTfVLi2p.png align="left")

2 . Click Add Entity.<br>
3 . In the New Entity dialog, type “My-Project”.<br>
![Screenshot (174).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665926180925/YpuVxsW1h.png align="left")

Now We have a new entity named "My-Project". You will notice that the added entity comes with auto-generated values such as “Plural Display Name” and some default fields – **ID**, **Created At**, and **Updated At**.

### Step 3 - Add Entity Fields
-> To create new entity field just click on "Add Field" then write name of new field and following things:

- **Name **– for saving the project name
- **Description **– for saving a more detailed description of the project
- **Start Date** – for saving the date on which this project starts
- **Owner **– for assigning a user to be an owner of the project

 
![Screenshot (175).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665928941718/9dEUApiQm.png align="left")

### Step 4 - Create Roles
Click the Roles icon on the main menu (left sidebar) to reach the Roles page. Here you see all the roles in your service.

![Screenshot (176).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665929204695/OmgmMbf0t.png align="left")
For Example:<br>
1 . In the Type role name text box, type "Admin".<br>
2 . Click Add Role (or just press Enter). The new role is added to the list.<br>
3 . Repeat these steps to add the "Manager" role.<br>

![Screenshot (177).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665929564012/-CKoNoKzB.png align="left")

### Step 5 - Set Access Permissions
In order to allow users to access the entity, we need to set its permissions.<br>
Permissions can be controlled separately for each of the following actions:<br>

- **View**
- **Create**
- **Update**
- **Delete**
- **Search**

These actions can be set to one of the following:

- **Public **- no authentication is required, so the action is available to all users, not only those with defined roles
- **All Roles **- all roles can perform the action
- **Granular **- only specified roles can perform the action

->In the following example, we use the Granular setting to find tune the permissions for a role.

1 . On the Overview page, click Go to Entities, or from the main menu (left sidebar) click the Entities icon.<br>
2 . Click the "My-Project" entity.<br>
3 . In the Project page click the Permissions tab. This opens the Permissions settings.<br>
4 . By default, all actions (View, Create, Update, Delete, and Search) are set to All Roles.<br>
5 . Fine tune permissions by changing the Delete permissions from All Roles to Granular and then select from the displayed roles the Manager role. This ensures that only users with the Manager role can delete projects.<br>


![Screenshot (178).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665929966596/ZL1AETYHR.png align="left")

### Step 6 - Commit Your Changes
While working in Amplication your changes are saved automatically, but are not committed. Only committed changes will be included in the next version of your generated application.<br>

In the Pending Changes control in the right sidebar you can see the list of pending changes that are waiting to be committed.

We'll now make our first commit.

In this page, you can see that the creation of the Project entity hasn't been committed.

1 . In the commit message dialog, write a description of the changes you're committing. For example: "Added Project Entity and Manager and Admin roles".<br>
2 . Click Commit Changes. All changes are committed. A build of the first version of your service is automatically created!<br>
3 . After the build process completes, click the download icon in the Generate Code row to get a .zip file of your app. It is now ready to be deployed anywhere you want.🚀

 
### That's it,<br>This is the whole process of creating a new service to commit it 😁<br><br>

## How to view the Generated Code ? 🙄❗
On the Overview page, click View Code, or click the Code View icon on the menu.<br>
Then, select a Commit from the Select Commit list.


![Screenshot (180).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1665931205352/fQfvWqP4d.png align="left")

### Checkout here: [Amplication](https://amplication.com/)
### Thanks for reading 🤓📖
