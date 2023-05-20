# Spectrum-Task-Integrated-Email-Excel-Regex

Note :- I have kept the input box for the process you want see. Please select the process and that process will run.


1) Excel Automation :- Here we are reading the excel which is kept in the Data folder.
                                         Have a loop into the excel and decide which value, you want to check.
     Then,
             i)  User can provide the input value which you want to check the count and column name.
             i)) If user do not provide value then it will take  values and column by itself and provide the count 

2) Email Automation :- Here We are taking the Email adress, Name, Body, Subject from config file.
              Sending mail to sender's email address with attachment, which we have given in config file.
              If attachment is missing in the folder then we are sending the mail with different body and with attachment.

3) RegEx Automation :- Here, we have taken the input string which is given in the task word file.
       Here we are fetching emails and phone number using Uipath matches activity as well as regex direct expression and priting            values at the end.
