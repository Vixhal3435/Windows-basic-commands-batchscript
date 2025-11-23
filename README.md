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

<img width="742" height="47" alt="image" src="https://github.com/user-attachments/assets/49b4da86-c1e6-4492-8eba-68cd7d0d3102" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"

<img width="744" height="40" alt="image" src="https://github.com/user-attachments/assets/1f378f9c-1851-4f37-b9d3-9454e3455d68" />

## COMMAND AND OUTPUT


Create the file Rose.txt

<img width="792" height="436" alt="image" src="https://github.com/user-attachments/assets/34f78b53-9762-4df7-961b-5e30eccddfe1" />

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection

<img width="974" height="129" alt="image" src="https://github.com/user-attachments/assets/77964a52-9881-420f-b9d8-6f8e79996744" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt

<img width="895" height="144" alt="image" src="https://github.com/user-attachments/assets/b1fe40cc-548b-41ad-b3c3-469f3a3def0a" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="726" height="35" alt="image" src="https://github.com/user-attachments/assets/a6544ff8-7637-449b-9d23-7021a6118039" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="697" height="344" alt="image" src="https://github.com/user-attachments/assets/87b79def-2d34-4839-8fc1-fc028baacdcf" />

## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="701" height="345" alt="image" src="https://github.com/user-attachments/assets/2f0e5a6f-e622-4a78-96c2-ed8ce53bf7d5" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="841" height="225" alt="image" src="https://github.com/user-attachments/assets/c21e59fe-4eba-461d-939a-33d543a89d98" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

<img width="1025" height="76" alt="image" src="https://github.com/user-attachments/assets/3f3fd85b-24e2-4135-8be3-903217f5da35" />




## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

<img width="1027" height="241" alt="image" src="https://github.com/user-attachments/assets/51af2337-df59-4b3e-bef1-00cb124bb32d" />


## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

<img width="990" height="184" alt="image" src="https://github.com/user-attachments/assets/f3b821e9-abb8-422a-9013-0a9ceaef33c3" />



## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

<img width="1008" height="173" alt="image" src="https://github.com/user-attachments/assets/df4b9e88-3579-4b69-9d99-942a5788908a" />

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.

<img width="922" height="397" alt="image" src="https://github.com/user-attachments/assets/c9508088-5201-4668-9807-b26e4c1fd758" />


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

