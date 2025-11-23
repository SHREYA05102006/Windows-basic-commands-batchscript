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
<img width="559" height="57" alt="image" src="https://github.com/user-attachments/assets/5a5c4266-f418-4377-843f-c1899c5bb185" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="552" height="60" alt="image" src="https://github.com/user-attachments/assets/861e4627-d4f5-4be4-98f0-4d197a337697" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="786" height="232" alt="image" src="https://github.com/user-attachments/assets/dbfa29a5-5d06-471b-8243-9242b1350892" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="762" height="122" alt="image" src="https://github.com/user-attachments/assets/b5f01e96-9fa9-4a8a-952d-3f616fadf6cf" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="614" height="139" alt="image" src="https://github.com/user-attachments/assets/aa2afc05-ca31-47dc-a8a4-a09dbb3000fb" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="508" height="47" alt="image" src="https://github.com/user-attachments/assets/bb972f41-dcb7-459a-ac5f-c06c88620193" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="469" height="190" alt="image" src="https://github.com/user-attachments/assets/f07b0027-0195-439f-9e98-2aa71d1d5eac" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="561" height="540" alt="image" src="https://github.com/user-attachments/assets/cc8fd7b0-8790-4430-9801-2550f385e1c0" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="649" height="248" alt="image" src="https://github.com/user-attachments/assets/3b28b0fe-76f7-4116-a4c9-ef24d5b4678c" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="523" height="127" alt="image" src="https://github.com/user-attachments/assets/faf2fa4b-d867-4ef1-a0d9-f2dc26e2fa3c" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="673" height="265" alt="image" src="https://github.com/user-attachments/assets/d944eafd-d661-4e47-8c84-c53e8dc70f22" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="394" height="200" alt="image" src="https://github.com/user-attachments/assets/27e6034a-0083-42be-8bc5-0c8f91371137" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="465" height="127" alt="image" src="https://github.com/user-attachments/assets/132096d4-f182-44ac-bc09-ce5fc0af7170" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="531" height="428" alt="image" src="https://github.com/user-attachments/assets/df7b3969-0451-4823-8aa5-eb1713f503dc" />



# RESULT:
The commands/batch files are executed successfully.

