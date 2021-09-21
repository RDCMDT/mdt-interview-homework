### Home Assignment 
This assignment will be similar to what you will be doing in your daily task. As a mobile developer, you will be creating new features by working with the various stakeholders to deliver great user experience to our customers. 

In your day to day work, you will be liaising with the various departments, from backend to product owners to understand the requirements, refine stories and deliver what is needed in scrum sprints. 

In this assignment, the backend, a mock server, is already setup and you will just need to deliver the UI portion of it. 

We have also provided wireframes for your reference but please feel free to amend it as you see fit and we can walkthrough your ideas during your follow up interview. 

5 APIs have been provided for you to complete it:
1. authenticate/login 
2. account/balances
3. account/transactions
4. account/payees
5. transfer

Your project should utilise all the APIs and we will evaluate your project based on the following project criteria:

1. Project runs as expected without crashing
2. User is able to login
3. User is able to see the balances / transactions in the account
4. User is able to retrieve his/her list of payees
5. User is able to make a transfer 

You are free to use any other libraries that you feel is needed for this project. 

Have fun with the project and good luck!

### Setup Mock Server
1. Clone the repo into your local machine.
2. Run `npm install` to install the dependencies.
3. Run `npm start` to start the mock server. Your mock server should start on `http://localhost:8080` by default.
4. Install postman into your computer and import the [postman collection](https://github.com/RDCMDT/mdt-mockserver/tree/master/postman_collection) we provided.
5. You may now interact with the mock server via the Restful APIs. Please find below, the sample header and sample body for the APIs provided. 


### Prerequisites
Node.js


### Instruction
1. Authenticate the user and retrieve the jwt token via "/authenticate/login"
   ```
   username: ocbc
   password: 123456
   ```
2. In the subsequence apis call, pass the token into the header.
   ```
   Content-Type: "application/json"
   Accept: "application/json"
   Authorization: {{your-token}}
   ```

### Submission
Upload to github and submit a link to your project. 


### Evaluation Criteria

* The required functions are working:
	* Login
	* Display dashboard	
	* Make transaction
	* Refresh

* The code is well-designed
	* Function
	* Interaction

* The UI is sensible and looks good

* The code isn't more complex than it needs to be

* Code has appropriate unit tests
	* Tests are well designed
	* Coverage

* Code is properly documented in README.md