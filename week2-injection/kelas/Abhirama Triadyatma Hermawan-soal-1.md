# Login Admin
Log in with the administrator's user account.
# Source
https://juice-shop.herokuapp.com/#/score-board?categories=Injection&showDisabledChallenges=false 

# Step by step


Start with a simple SQLi attack with inserting ``'`` as a query 
<img width="1917" height="980" alt="Screenshot 2025-09-09 151732" src="https://github.com/user-attachments/assets/2df1770c-e3e2-4b82-b610-caabf76bd881" />
After inspecting the network console we found a 500 error status. To continue we can manipulate the query to ``' OR true--`` 
<img width="1917" height="988" alt="Screenshot 2025-09-09 152234" src="https://github.com/user-attachments/assets/ec0de4bc-f756-4850-a7f6-fb57a3bacf9a" />
with that query we've been able to SQLi succesfully and login as the admin
<img width="1914" height="993" alt="Screenshot 2025-09-09 151812" src="https://github.com/user-attachments/assets/4abcd02e-be7c-43b3-bf64-1a5d0e905b75" />
