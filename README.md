# chatapps

1. Download the files then extract in a folder.
2. Open in code editor (e.g VScode).
3. Open VScode Terminal (or your preferred code editor terminal).
4. Change directory to api ("\chatapps-main> cd api").
5. Once in api run "npm install express"
6. Then run "nodemon index.js"

	Terminal should look like this

	"[nodemon] starting `node index.js`
	 Connected Successfully"
	
7. Open another terminal and Change directory to client folder

	"cd client" ("\chatapps-main> cd client").

8. Run (or install) "npm i" ("chatapps-main\client> npm i")
9. Run "yarn dev" and click "Local" (copy paste the local to a browser).

e.g
	
  VITE v4.2.2  ready in 355 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h to show help

10. Copy paste the "local" to another browser (e.g Firefox or just open Guest in Chrome). 
You should have 2 localhost address opened in two different browsers.

11. Once you are in the Login page, click Register (for new users).
12. Type desired "Username" and "Password"
13. Repeat step 11 & 12 on the other browser.

14. Before sending messages go to code editor and open Chat.jsx (client > src > Chat.jsx) and save it (ctrl s)
15. Once Logged in, click the user and type in message in the message box and press enter or click the send icon.
16. In the other browser click the user and check if messages have been recieved. *In case messages is not going throught real time, try step # 14.
17. Try sending an attachment.
18. Try Logging out and relogging in using the same credentials (using Login) or create another users by clicking Register.







