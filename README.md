# Admin_Task_Management_Using_Angular
this app helps admin to manage his tasks.
how to run?
1.first download and extract both files.
3.open the complaints2312024 folder in vscode.
2.open the complaints-1 folder in sts(spring tool suite) workspace.
3.in sts,double click on complaints-1,in src folder, open application.properties.
4.type url and username and password as per your local database.
5.run this project by right clicking on main complaints-1 folder and run as -> springboot app.
6.run the project at vscode by new terminal and enter ng serve.
7.now go to localhost:4200 on browser and do multiple signups as a users using different emails and passwords.
8.you have to set one user as admin.to do this open sql database and hit the following update command and commit command:
UPDATE complaints3feb2024 SET ROLE='admin' WHERE EMAIL='enter the email you want to make';
commit;
9.Done.Now you can add(CREATE) and see(READ) and delete (DELETE) your tickets/complaints.
10.The Admin can see(READ) and solve(UPDATE) the tickets by clicking solve button.this updates the status from "pending" to "closed".
Thank You.
