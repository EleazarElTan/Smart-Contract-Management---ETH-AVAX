#  Smart-Contract-Management---ETH-AVAX

For this project, create a simple contract with 2-3 functions. Then show the values of those functions in frontend of the application.

#  Installing
https://github.com/MetacrafterChris/SCM-Starter
+  You can clone the repository using the git clone <link to repository> command through your terminal.
+  You can also clone it through github desktop by clicking the down arrow button beside the code button and selecting open with github desktop

#  Executing program
+  Inside the project directory, in the terminal type: npm i
+  Open two additional terminals in your VS code
+  In the second terminal type: npx hardhat node
+  In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
+  Back in the first terminal, type npm run dev to launch the front-end.
+  Install the metamask extension in your web browser
+  Add a network manually in your metamask with these fields
Name: (can be anything you would like)
RPC URL: http://127.0.0.1:8545/
Chain ID: 31337
Currency Symbol: ETH
+  Click save
+  Switch to your created network
+  Go back to the terminal where you entered npx hardhat node and copy the private key of Account 0
+  Import the account to Metamask

After executing these steps you will now be able to use the program by using the link given after your npm run dev command. It should look something like this  http://localhost:3000 link
