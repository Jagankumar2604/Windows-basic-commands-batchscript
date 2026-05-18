# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

Remove the directory "my-folder"

z<img width="510" height="187" alt="image" src="https://github.com/user-attachments/assets/2b0e214c-efc3-4dd0-bbbe-20847a3d6abf" />

## COMMAND AND OUTPUT


<img width="511" height="113" alt="image" src="https://github.com/user-attachments/assets/bc4819d1-2470-44b6-9e1b-72e5e38872f9" />

Create the file Rose.txt

## COMMAND AND OUTPUT


<img width="515" height="367" alt="image" src="https://github.com/user-attachments/assets/b46a1ca7-f01c-45ac-b863-91a74d28f47b" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="1237" height="132" alt="image" src="https://github.com/user-attachments/assets/ef28c630-3094-49a1-b85d-5de80a174a8b" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="757" height="177" alt="image" src="https://github.com/user-attachments/assets/1d416748-7cd4-4d07-9a06-f07db7e6dabe" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="752" height="187" alt="image" src="https://github.com/user-attachments/assets/6b96c4ad-85c8-4422-b0fe-096d4dccb431" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="752" height="187" alt="image" src="https://github.com/user-attachments/assets/9187bbf7-db62-4f64-8990-de4ba3eb5f50" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="751" height="295" alt="image" src="https://github.com/user-attachments/assets/734d93ad-64b6-4876-a3a3-87d5fcd4356d" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="798" height="253" alt="image" src="https://github.com/user-attachments/assets/3a990f8b-e990-4189-8225-dc875c09bea5" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

