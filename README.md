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
![Screenshot 2025-05-24 130658](https://github.com/user-attachments/assets/62bf5a4f-20d9-4617-9b48-370779fe877a)

Remove the directory "my-folder"
## COMMAND AND OUTPUT
![Screenshot 2025-05-24 130726](https://github.com/user-attachments/assets/f0840799-4d20-4e55-b0f0-2be8e27c28cc)

Create the file Rose.txt

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 130758](https://github.com/user-attachments/assets/3f666eb7-a5cf-49d6-9309-4c4a1f20c02d)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 130844](https://github.com/user-attachments/assets/dd27c03e-1cf6-490d-82f3-78a4f05a9b74)

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 130911](https://github.com/user-attachments/assets/940f1c80-440c-45fa-a4a5-a2fa57344132)

Remove the file hello1.txt

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 130935](https://github.com/user-attachments/assets/bee057df-9054-44e6-a4ce-0d0eecbf4b6b)

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 131003](https://github.com/user-attachments/assets/4942359e-8075-41c4-a056-50e35b650ceb)

List out all the associated file extensions 

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 131100](https://github.com/user-attachments/assets/d25b089b-e4ad-4053-999e-b5ec75e0143f)

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
![Screenshot 2025-05-24 131134](https://github.com/user-attachments/assets/af819bd4-68a3-4df8-9a59-c2da04fe1475)

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
### PROGRAM
![image](https://github.com/user-attachments/assets/052e57b8-83ab-405c-a904-70eae3c3fd24)

## OUTPUT

![Screenshot 2025-05-24 181454](https://github.com/user-attachments/assets/f8a3414f-7f27-4d56-98f6-7312dc24b1e3)


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

### PROGRAM
![image](https://github.com/user-attachments/assets/c80fbb61-a805-4bbb-8577-5d2b2dc989f1)


## OUTPUT

![Screenshot 2025-05-24 181501](https://github.com/user-attachments/assets/44395b06-3319-4b12-a0dd-25e45b69ad1b)



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

### PROGRAM
![image](https://github.com/user-attachments/assets/72d1817b-a19d-447e-bf63-1c64ead7d42f)



## OUTPUT

![Screenshot 2025-05-24 181615](https://github.com/user-attachments/assets/a0a8fada-c60c-4e8f-9977-90d0b8f103be)



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

### PROGRAM
![image](https://github.com/user-attachments/assets/54de3b69-e664-46f0-8eb6-94c78d63a2f4)


## OUTPUT
![Screenshot 2025-05-24 181830](https://github.com/user-attachments/assets/bcc930e7-6c89-4c92-9ca1-d7f83b4e4b20)


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.
### PROGRAM
![image](https://github.com/user-attachments/assets/52f31afb-6dd1-4457-af6f-95fbd2a71c9b)

## OUTPUT
![Screenshot 2025-05-24 181835](https://github.com/user-attachments/assets/a13d8801-9f62-4f8e-8d21-906b90ebb846)



# RESULT:
The commands/batch files are executed successfully.

