# chatapps

1. Download the files then extract in a folder.
2. Open in code editor (e.g VScode).
3. Open VScode Terminal (or your preferred code editor terminal).
4. Change directory to api ("\chatapps-main> cd api"). ![image](https://user-images.githubusercontent.com/39289957/234757642-3c5ed7d0-4e4e-46aa-8092-0196bce8d4cd.png)

5. Once in api run "npm install express" ![image](https://user-images.githubusercontent.com/39289957/234757914-3a5793e8-a31b-4645-9b69-a2c2f9d48e5f.png)

6. Then run "nodemon index.js"

	![image](https://user-images.githubusercontent.com/39289957/234758023-0269c000-07d0-4ac2-8bdf-2d96986a1cc2.png)

	
7. Open another terminal and Change directory to client folder

	![image](https://user-images.githubusercontent.com/39289957/234758088-95a6ec36-0523-4d6d-b08e-385c98397f0e.png)

8. Run (or install) "npm i" ("chatapps-main\client> npm i") ![image](https://user-images.githubusercontent.com/39289957/234758174-0d72bdc4-972f-46cc-987a-9280951f4106.png)

10. Run "yarn dev" and click "Local" (copy paste the local to a browser).

	e.g

	  VITE v4.2.2  ready in 355 ms

	  ➜  Local:   http://localhost:5173/
	  ➜  Network: use --host to expose
	  ➜  press h to show help
	  
	  ![image](https://user-images.githubusercontent.com/39289957/234757496-257ab697-2ba9-4e83-9163-79bb6c7cdee9.png)


10. Copy paste the "local" to another browser (e.g Firefox or just open Guest in Chrome).  You should have 2 localhost address opened in two different browsers.

11. Once you are in the Login(or Register) page, click Register (for new users).
12. Type desired "Username" and "Password"
13. Repeat step 11 & 12 on the other browser.

14. Before sending messages go to code editor and open Chat.jsx (client > src > Chat.jsx) and save it (ctrl s)
15. Once Logged in, click the user and type in message in the message box and press enter or click the send icon.
16. In the other browser click the user and check if messages have been recieved. *In case messages is not going throught real time try step # 14.
17. Try sending an attachment.
18. Try Logging out and relogging in using the same credentials (using Login) or create another users by clicking Register.







