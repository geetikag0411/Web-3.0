# Web-3.0
Here in this code, "MetaCoin" class was given in the template and "Loan" is the derived class.
"isOwner" is a modifier that allows the function to work only when "msg.sender" is the owner.
"getCompoundInterest" is function that takes principle,rate,time as input and gives the compound interest using "muldiv" function,here the Principal is first 
multiplied by 1e8 and then the final amount to pay is divided by 1e8 to improve precision.

Example
![image](https://user-images.githubusercontent.com/96648258/175776278-29ec4869-225b-477c-a183-2b9e69ed752b.png)

Taking the highlighted account is the owner and the account below that is creditor

"getBalance" function
![image](https://user-images.githubusercontent.com/96648258/175776360-d04afb6b-811a-453e-80cc-7b2f5e189a53.png)

"getOwnerBalance" ![image](https://user-images.githubusercontent.com/96648258/175776463-334bb87a-c702-4d6e-98e1-1a0093455578.png)

"reqloan" and "viewDues" ![image](https://user-images.githubusercontent.com/96648258/175776601-7fbe0fba-56fb-48b2-b7f5-1af994e58c2f.png)

after using "settleDues","getOwnerBalance","viewDues" and "getBalance"
![image](https://user-images.githubusercontent.com/96648258/175776760-e70e08a8-c26e-407f-bbd6-43ef46449ea1.png)




