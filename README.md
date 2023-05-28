# Core_Java_ATMInterface
This ATM project is a core Java Project which is created using core java concepts like Encapsulation,Exception Handlings,Functions,Statements, Random Password Generation. MySql Database to connect the Java Program to database. All the user object data are get stored in database .Withdraw, Deposit, CheckBalance,  ChangePin ,AccountBal func are used 

First it will ask new user or existing.

If new user, then it will create new object and add all the information related to that user like name, phoneNo , after that create random cardno of length 12 and ask for create new pin and add money to the account .after that, it will send all the data to the table.

if existing user, then it will ask for cardNo and pin then validate with the cardno ,pin that present in the table. 
If correct it will allow for further operations like withdrawl,deposit,
checkBalance , accountInfo, pinChange.
