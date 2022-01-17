# ATM_Machine


Step 1  - START
Step 2  - call the "welcomeLog()" function.
Step 3  - Print the welcome statement . Declare the integer "cardnumber" and take its input from the user .
Step 4  - Initialize the "InitialAmount" static integer variable using the rand function.
Step 5  - Initialized the "pin" static integer variable with the help of generatePin() function.

Step 6  - Call the "atmOptions()" function.
Step 7  - Print 4 options i.e. Cash Withdrawal, Cash Deposit, Balance Enquiry, Exit.
Step 8  - Ask the user to select any of the option . 
Step 9  - Declare the integer "SelectedOption" and take its input from the user .
Step 10 - Declare the integer "temPin".

Step 11 - Enter the switch statement with the integer "selectedOption" and make 4 cases .    
Step 12 - If "selectedOption" is equal to 1 then enter case 1 and call the function "cashWithdrawal()".
Step 13 - If "selectedOption" is equal to 2 then enter case 2 and call the function "cashDeposit()".
step 14 - If "selectedOption" is equal to 3 then enter case 3 and then ask the user for the pin and if the "pin is equal to the original pin" then call the function "balanceEnquiry()" or else print "The pin was incorrect".
step 15 - If "selectedOption" is equal to 4 then enter case 4 and call the function "Exit()".
Step 16 - If the "selectedOption" value is other than 1 -4 then ,print "Invalid Input " and call "Exit()" function .

Step 17 - If "selectedOption" is equal to 1 and the "cashWithdrawal()" is called then print the message "Enter Your Pin " and then declare the integer "temPin" inside the callWithdrawal() function and take its input from the user . 
          Check if "tempPin is equal to pin", then print "Enter Withdrawal Amount" and declare the integer "withdrawalAmount" and take its input from the user.
          Check if "withdrawalAmount is greater than InitialAmount, then display the message "Insufficient Amount in Your Account" and call the "balanceEnquiry()" function to show "Available Balance" to the user.
          Or else display the message "The pin was incorrect".	


Step 18 - If "selectedOption" is equal to 2 and the cashDeposit() is called then print the message "Enter Your Pin " and then declare the integer "temPin" inside the cashDeposit() function           and take its input from the user . 
           Check if "tempPin == pin" ,if its true then print the message "Enter Deposit Amount" then declare the integer "tempDepoAmount" and take the input from the user the amount he/she            want to withdrawal.
            After entering the amount add the tempDepoAmount with InitialAmount and upadate the initial amount " InitialAmount = InitialAmount + tempDepoAmount" and then call the                      "balanceEnquiry()" function .
            if  "tempPin == pin" is false, print "The pin was incorrect".
	

Step 19 - If "selectedOption" is equal to 3 and the balanceEnquiry() function is called then display the Initial amount with the message of "Available Balance ".


step 20 - If "selectedOption" is equal to 4 and Exit() is called the print the message "Thank You ! Visit Again" . 

													
