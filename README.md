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
<img width="398" height="55" alt="image" src="https://github.com/user-attachments/assets/9764b4c0-bde4-4fba-a81c-84f90be7f897" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="381" height="49" alt="image" src="https://github.com/user-attachments/assets/9c3a1b42-890a-41cb-8c37-77c4629bb4b1" />

## COMMAND AND OUTPUT
Create the file Rose.txt
<img width="747" height="396" alt="image" src="https://github.com/user-attachments/assets/8bda34df-b549-4a6b-9b75-feea9b7bb9a1" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="748" height="111" alt="image" src="https://github.com/user-attachments/assets/bc274e6c-f215-4d7a-916e-76dc5d50e38e" />

## COMMAND AND OUTPUT
Copy the file hello.txt into the file hello1.txt
<img width="559" height="76" alt="image" src="https://github.com/user-attachments/assets/a8406493-d740-4197-b9c1-346354790dd7" />

## COMMAND AND OUTPUT
Remove the file hello1.txt
<img width="397" height="55" alt="image" src="https://github.com/user-attachments/assets/3be29a33-ca65-4821-9cd6-6603f2b371b6" />

## COMMAND AND OUTPUT
List out the file hello1.txt in the current directory
<img width="522" height="177" alt="image" src="https://github.com/user-attachments/assets/4ea1b4c3-c876-4c96-b5e4-8d29ca07a877" />

## COMMAND AND OUTPUT
List out all the associated file extensions 
<img width="690" height="1052" alt="image" src="https://github.com/user-attachments/assets/4f588762-3d77-4fe7-a295-b001e87058a4" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="646" height="198" alt="image" src="https://github.com/user-attachments/assets/5eb8725c-335c-4611-baa5-1daca1727089" />

## COMMAND AND OUTPUT
## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

## OUTPUT

<img width="564" height="111" alt="image" src="https://github.com/user-attachments/assets/1cd8924a-ac47-48ae-b3f5-1a7e4ae3486e" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="724" height="280" alt="image" src="https://github.com/user-attachments/assets/7f62a6e8-27eb-4404-be00-fb652828dc43" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="531" height="177" alt="image" src="https://github.com/user-attachments/assets/00932b7c-f10f-4aab-9c34-c49502689bed" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="437" height="93" alt="image" src="https://github.com/user-attachments/assets/fb51e0ec-5168-411f-8d78-ceaea789e1aa" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="482" height="418" alt="image" src="https://github.com/user-attachments/assets/0ca5c025-431f-45cb-a014-358d54b14beb" />


# RESULT:
The commands/batch files are executed successfully.

