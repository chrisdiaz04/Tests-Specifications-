Block18 Folder that includes a txt file.


if unable to read, here are the contents:
Unit tests - multiplication function takes two numbers and returns the product :
    expect [multiplication(x, y)] to return [number]
    expect [multiplication(3, 5)] to return [15]
    expect [multiplication(0, {any number})] to return [0]
    expect [multiplication ("string", y)] to return "Error"
    expect [multiplication()] to return "Error"

Unit tests - concatOdds function that takes two arrays of integers and returns a single array containing only odd numbers from both arrays. New array 
needs to have odd integers in ascending order :
    expect [concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1])] to return [[-1, 1, 3, 9, 15]]
    expect [concatOdds()] to return "Error"
    expect [concatOdds([2, 2, 4], [8, 2, 2, 2, 4, 16, -2])] to return an empty array since no odds are in the arrays[[]]
    if array has duplicates, expect array to just display only on of the duplicates 

Functional tests:
    if the user doesn't have anything in their cart, they are alerted that they have zero items inside their cart and need to select an item to proceed 
    
    When user tries to checkout, prompt them if they want to sign in or continue as guest
    
    When user chooses to sign in, prompt them to enter their user and password 
        If the user doesn't enter anything or enters the wrong credentials, prompt them to try again
        when the user enters their credentials, they can proceed to checkout as a user
   
    When the user chooses to continue as a guest, they are taken to checkout their cart as a guest 
        when the user checks out they are prompted to enter information so that the order can be proccessed correctly 
        if the guest doesn't enter any of their information they are prompted to enter the required information to make the successful purchase 
   
    When valid information has been inputted, a prompt should appear that their purchase has went through successfully 
     if they dont't have an account, the user is prompted if they want to sign up or save their information for their next purchase

     prompt the user "Thank you for shopping with us" 
