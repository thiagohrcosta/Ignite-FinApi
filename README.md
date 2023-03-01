![enter image description here](https://camo.githubusercontent.com/c1961440b3cd295d2e75cbe71c7177fb4474f5eb8cbe53e359b112e4128723ac/68747470733a2f2f7265732e636c6f7564696e6172792e636f6d2f646c6f6164623262782f696d6167652f75706c6f61642f76313637343532333539362f34326531616238302d373761662d313165622d396530372d3437663965343662336536655f61786f636e6e2e706e67)

# FinApi API (NodeJS)
**Requirements**

 - It should be possible to create an account 
 - It should be possible to fetch the customer's bank statement
 - It must be possible to make a  deposit 
 - It must be possible to perform a withdrawal It should be possible to search the customer's bank statement by date 
 - It must be possible to update customer account data
 - Must be possible to get customer account data It must be possible to delete an account

**Business rules**

 - It should not be possible to register an account with an existing CPF
 - It must not be possible to deposit into a non-existing account 
 - It must not be possible to fetch a statement in a non-existing account
 - It must not be possible to withdraw to a non-existing account
 - It must    not be possible to delete a non-existing account It should not be
   possible to withdraw when the balance is insufficient
