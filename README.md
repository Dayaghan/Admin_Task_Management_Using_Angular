# Admin_Task_Management_Using_Angular
this app helps admin to manage his tasks.<br>
how to run?<br>
1.first download and extract spring file.<br>
2. the second file link is <a href="https://drive.google.com/file/d/15uX3FHATzdp0qRIpf2FMSQFJzpqzZrEu/view">click here</a><br>
2.extract and open the complaints2312024 folder in vscode.<br>
3.open the complaints-1 folder in sts(spring tool suite) workspace.<br>
4.in sts,double click on complaints-1,in src folder, open application.properties.<br>
5.type url and username and password as per your local database.<br>
6.run this project by right clicking on main complaints-1 folder and run as -> springboot app.<br>
7.run the project at vscode by new terminal and enter ng serve.<br>
8.now go to localhost:4200 on browser and do multiple signups as a users using different emails and passwords.<br>
9.you have to set one user as admin.to do this open sql database and hit the following update command and commit command:<br>
UPDATE complaints3feb2024 SET ROLE='admin' WHERE EMAIL='enter the email you want to make';<br>
commit;<br>
10.Done.Now you can add(CREATE) and see(READ) and delete (DELETE) your tickets/complaints.<br>
11.The Admin can see(READ) and solve(UPDATE) the tickets by clicking solve button.this updates the status from "pending" to "closed".<br>
Thank You.
