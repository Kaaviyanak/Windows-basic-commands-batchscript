# Ex08-Windows-basic-commands-batchscript
# NAME: KAAVIYAN.K

# REG NO: 212224240066

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

#### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

#### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
#### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
### Exercise 1: Basic Directory and File Operations

Create a directory named "my-folder"
### COMMAND AND OUTPUT
<img width="606" height="223" alt="1 mkdir" src="https://github.com/user-attachments/assets/fa6167c1-7a2c-4948-a998-db49461c017b" />


Remove the directory "my-folder"
### COMMAND AND OUTPUT
<img width="842" height="371" alt="image" src="https://github.com/user-attachments/assets/6022a352-2b44-4025-81ee-125fcecbc4cc" />


Create the file Rose.txt
### COMMAND AND OUTPUT

<img width="828" height="352" alt="image" src="https://github.com/user-attachments/assets/07059174-4bfb-4a9b-869d-fc0894314753" />


Create the file hello.txt using echo and redirection
### COMMAND AND OUTPUT
<img width="960" height="121" alt="image" src="https://github.com/user-attachments/assets/26c6180e-9e85-456a-9ad9-b4d0a4a4fd27" />


Copy the file hello.txt into the file hello1.txt
### COMMAND AND OUTPUT
<img width="892" height="143" alt="image" src="https://github.com/user-attachments/assets/6e1c792d-de10-44e5-8b07-4eb1413316e5" />


Remove the file hello1.txt
### COMMAND AND OUTPUT
<img width="782" height="221" alt="image" src="https://github.com/user-attachments/assets/6a585b3d-d308-49c8-b57b-27cb3b58c110" />


List out the file hello1.txt in the current directory
### COMMAND AND OUTPUT

<img width="757" height="1059" alt="image" src="https://github.com/user-attachments/assets/199f45c4-bce4-4b18-8a7a-434206d2d973" />



List out all the associated file extensions 
### COMMAND AND OUTPUT
<img width="863" height="1106" alt="image" src="https://github.com/user-attachments/assets/f8e57bc6-8d3e-4a30-a643-201d7411b75d" />


Compare the file hello.txt and rose.txt
### COMMAND AND OUTPUT

<img width="826" height="188" alt="image" src="https://github.com/user-attachments/assets/dffc3679-c894-4e70-8800-f459e03a36c3" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

### OUTPUT

<img width="697" height="89" alt="image" src="https://github.com/user-attachments/assets/73ebd8cf-6ba8-4ac4-b2e1-df6368ef223b" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.

### OUTPUT
<img width="693" height="260" alt="image" src="https://github.com/user-attachments/assets/4b0f04dd-a5fd-4e75-a8c4-2748774d43e3" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.

### OUTPUT
<img width="715" height="209" alt="image" src="https://github.com/user-attachments/assets/891ea277-a4bb-40f4-ace5-2dd683c64fc1" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

### OUTPUT
<img width="696" height="111" alt="image" src="https://github.com/user-attachments/assets/b7b24a1e-7b35-4ff2-a4d7-945de048ff00" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


### OUTPUT
<img width="753" height="442" alt="image" src="https://github.com/user-attachments/assets/4be55db8-f190-4af4-a330-561271f8809b" />


# RESULT:
The commands/batch files are executed successfully.
