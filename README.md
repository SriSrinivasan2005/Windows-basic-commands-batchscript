# Windows-basic-commands-batchscript
# Ex08-Windows-basic-commands-batchscript

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
![1](https://github.com/user-attachments/assets/eaa04f08-61bd-48f5-be89-c00bc0a12a22)

Remove the directory "my-folder"

## COMMAND AND OUTPUT
![2](https://github.com/user-attachments/assets/099c24b1-f018-485b-a5f5-c597bda66dff)


Create the file Rose.txt

## COMMAND AND OUTPUT
![4](https://github.com/user-attachments/assets/403b6da9-c3d6-451c-b2f3-0b13c61ce548)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
![5](https://github.com/user-attachments/assets/dea44ea7-f3e3-4bfb-9841-db85c3890d6a)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![6](https://github.com/user-attachments/assets/503381f5-eb48-4e6c-a65a-d94fad959a13)

Remove the file hello1.txt

## COMMAND AND OUTPUT
![Screenshot 2025-05-19 135448](https://github.com/user-attachments/assets/b2c611ee-bbc9-4bc1-85ac-b145d95ce098)


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![7](https://github.com/user-attachments/assets/c6a9c89e-70fc-4204-ade5-4a9515afb91d)

List out all the associated file extensions 

## COMMAND AND OUTPUT

![8](https://github.com/user-attachments/assets/3c5f978d-9f20-4755-9574-5d927069815c)


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![9](https://github.com/user-attachments/assets/5802e631-1969-4002-91f0-a98ab60c8e89)


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

![10](https://github.com/user-attachments/assets/2b038bad-c46d-4a0b-a283-095d19515dc4)
![11](https://github.com/user-attachments/assets/279561ee-7188-41ac-beff-67c0790f83c7)

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
![12](https://github.com/user-attachments/assets/b25db9bc-e5cf-4756-b890-ec73da9c84c8)





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
![13](https://github.com/user-attachments/assets/254fac4a-def7-446b-b196-92df3c03a1c7)




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
![14](https://github.com/user-attachments/assets/7f3ab2b0-7837-4f95-9d7f-cd4c0603b600)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
![15](https://github.com/user-attachments/assets/3dac0fd0-4f3c-4c90-9a9e-e7fbc1b25c70)



# RESULT:
The commands/batch files are executed successfully.

