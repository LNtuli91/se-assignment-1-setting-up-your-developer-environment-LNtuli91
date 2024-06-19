[![Review Assignment Due Date](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15268786&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11.


Step 1: Download Windows 11 Installation Media
Visit the Windows 11 Download page on the Microsoft website.
Select Download now under the "Create Windows 11 Installation Media" section.

Step 2: Create Installation Media
Run the Media Creation Tool downloaded from the Microsoft website.>>Accept the license terms.>>Choose "Create installation media (USB flash drive, DVD, or ISO file) for another PC".>>Select language, edition, and architecture (64-bit).>>Choose USB flash drive or ISO file (for DVD) as the media type.>>Insert a USB flash drive (at least 8GB), and follow the prompts to create the installation media.

Step 3: Install Windows 11
Insert the installation media (USB drive or DVD) into your PC.>>Restart your PC, and boot from the installation media (you may need to change the boot order in BIOS/UEFI settings).>>Select your language, time, and keyboard preferences, then click Next.>>Click Install Now.>>Enter your product key, or select "I don't have a product key" if you are reinstalling Windows 11.>>Accept the license terms, then click Next.>>Choose Custom: Install Windows only (advanced) for a clean installation.>>Select the drive or partition where you want to install Windows 11, and click Next.

Step 4: Complete the Installation
Windows will install and your PC will restart several times during the process.>>Follow the on-screen instructions to set up Windows 11 (selecting region, keyboard layout, creating a user account, etc.).

Step 5: Install Updates and Drivers
Go to Settings > Update & Security > Windows Update to check for updates.>>Install all updates and any necessary drivers.


2. Install a Text Editor or Integrated Development Environment (IDE):
Download and Install Visual Studio Code:

Step 2: Backup Your Data
Backup important files to an external drive or cloud storage to prevent data loss.
Step 3: Download Windows 11 Installation Media
Visit the Windows 11 Download page on the Microsoft website.
Select Download now under the "Create Windows 11 Installation Media" section.
Step 4: Create Installation Media
Run the Media Creation Tool downloaded from the Microsoft website.

Accept the license terms.

Choose "Create installation media (USB flash drive, DVD, or ISO file) for another PC".


Select language, edition, and architecture (64-bit).

Choose USB flash drive or ISO file (for DVD) as the media type.


Insert a USB flash drive (at least 8GB), and follow the prompts to create the installation media.

Step 5: Install Windows 11
Insert the installation media (USB drive or DVD) into your PC.

Restart your PC, and boot from the installation media (you may need to change the boot order in BIOS/UEFI settings).


Select your language, time, and keyboard preferences, then click Next.


Click Install Now.


Enter your product key, or select "I don't have a product key" if you are reinstalling Windows 11.

Accept the license terms, then click Next.


Choose Custom: Install Windows only (advanced) for a clean installation.


Select the drive or partition where you want to install Windows 11, and click Next.


Step 6: Complete the Installation
Windows will install and your PC will restart several times during the process.

Follow the on-screen instructions to set up Windows 11 (selecting region, keyboard layout, creating a user account, etc.).


Step 7: Install Updates and Drivers
Go to Settings > Update & Security > Windows Update to check for updates.
Install all updates and any necessary drivers.
By following these steps, you will successfully download and install Windows 11 on your PC.


2. step by step of Install a Text Editor or Integrated Development Environment (IDE):
Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio


To install a text editor or Integrated Development Environment (IDE) like Visual Studio, follow these steps:

Step 1: Download Visual Studio
Visit this link: https://code.visualstudio.com/Download

Step 2: Run the Installer
Locate the downloaded installer (usually in your Downloads folder) and double-click to run it.>>Installer Setup:
The Visual Studio Installer will start. It might take a few moments to initialize.

Step 3: Select Workloads
Choose Workloads:
The installer allows you to choose workloads based on your programming needs. For example, select ".NET desktop development" for C# or "Desktop development with C++" for C++ programming.>>Individual Components:
You can also choose individual components if you have specific requirements.>>Installation Location:
You can customize the installation path if needed.

Step 4: Install Visual Studio
Start Installation:
Click on the "Install" button at the bottom right of the installer window.>>Installation Progress:
The installer will download and install the necessary files. This might take some time depending on your internet speed and the components selected.

Step 5: Launch Visual Studio
Complete Installation:
Once the installation is complete, you will see a "Launch" button. Click it to start Visual Studio.>>Sign In:
Sign in with your Microsoft account (optional but recommended for syncing settings and accessing additional features).


3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com:
Run the Installer:
Run the downloaded installer and follow the installation prompts. For Windows, you may see options for setting up your Git environment.>>Verify Installation:
Open a terminal (Command Prompt, PowerShell, or Terminal) and type the following command to verify the installation:>git --version
Step 1: Configure Git>>Set Your Username:>>Configure your Git username, which will be associated with your commits:>>git config --global user.name "Your Name">>Set Your Email:
Configure your email address, which will also be associated with your commits:>>git config --global user.email "you@example.com"
Step 2: Create a GitHub Account:>>Sign Up for GitHub:
Go to the GitHub website and click on "Sign up". Follow the instructions to create a new GitHub account.>>Verify Email:
Verify your email address by clicking on the verification link sent to your email.
Step 3: Initialize a Git Repository>>Create a Project Directory:>>Open a terminal and navigate to or create a new directory for your project:>>mkdir my-project>>cd my-project>>Initialize Git Repository:>>Initialize a new Git repository in your project directory:>>git init>>This creates a .git directory that tracks your project's version history.>>Create a README File:>>Create a README.md file for your project:>>echo "# My Project" > README.md
Stage the README File:>>Stage the file for commit:>>git add README.md>>Make Your First Commit:>>Commit the staged file with a message:>>git commit -m "Initial commit"
Step 4: Push to GitHub>>Create a New Repository on GitHub:
Go to GitHub and click on the "+" icon in the top right corner, then select "New repository". Name your repository and optionally add a description. Do not initialize with a README, .gitignore, or license.>>Get the Repository URL:
Copy the repository URL (HTTPS, SSH, or GitHub CLI) provided by GitHub.>>Add the Remote Repository: In your terminal, add the GitHub repository as a remote repository:>>git remote add origin https://github.com/yourusername/your-repository.git
Push Your Commit:>>Push your local commits to the GitHub repository:>>git push -u origin master

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  Click on the "Download Python" button. The website will automatically suggest the best version for your operating system.
  Step 1: Run the Python Installer
Locate the Installer:>>Once the download is complete, locate the installer file in your downloads folder and run it.>>Add Python to PATH:>>In the installer, check the box that says "Add Python to PATH". This is important for being able to use Python from the command line.>>Install Python:
Click on "Install Now". The installer will handle the rest of the process.
Step 2: Verify the Installation
Open Command Line:>>Open Command Prompt (Windows), Terminal (macOS), or a similar command line interface on your operating system.
Check Python Version:
Type the following command to check if Python was installed correctly and added to PATH:>>python --version
You should see the installed Python version number.
Step 3: Install pip (Python Package Installer)
Ensure pip is Installed:
pip usually comes pre-installed with Python. Check if pip is installed by running:>>pip --version
If pip is installed, you might want to upgrade it to the latest version:>>python -m pip install --upgrade pip
Step 4: Install Required Python Packages
Identify Packages:>>Identify the necessary Python packages for your project (e.g., numpy, pandas, flask).
Install Packages:>>Use pip to install these packages. For example:>>pip install numpy pandas flask
Step 5: Verify Package Installation. Check Installed Packages:
Verify that the packages are installed correctly by running Python and importing the packages:>>python
>>> import numpy
>>> import pandas
>>> import flask

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Choose the Installer:
Select the appropriate MySQL Installer (the web or full version). The full version includes all MySQL products and components.

after Clicking on the link button and follow the instructions to save the installer to your computer.
Step 1: Install MySQL
Run the Installer:>>Locate the downloaded installer file and double-click it to run the installer.>>Choose Setup Type:
You will be presented with different setup types. Select "Developer Default" if you are setting up MySQL for development purposes.>>Install Required Software:
The installer will check for required software. Click "Execute" to install any missing software (such as Visual Studio Redistributable).>>Select Products and Features:
Ensure the necessary MySQL products and features are selected, then click "Next".>>Apply Configuration:>>Click "Execute" to download and install the selected products.
Step 2: Configure MySQL Server
Configuration Overview:>>After the installation, the configuration steps will begin. Click "Next" to proceed through the configuration wizard.>>High Availability:
For most users, select "Standalone MySQL Server" and click "Next".>>Type and Networking:
Choose the "Development Computer" configuration. Ensure the port number is set to 3306 (default). Click "Next".>>Authentication Method:>>Choose "Use Legacy Authentication Method" if you need compatibility with older applications, otherwise, select the recommended "Use Strong Password Encryption". Click "Next".>>Root Password and User Accounts:
Set a strong root password and create any additional user accounts if necessary. Click "Next".>>Windows Service:
Configure MySQL as a Windows Service. Select "Run MySQL as a Windows Service" and optionally check "Start the MySQL Server at System Startup". Click "Next".>>Apply Configuration:
Click "Execute" to apply the configuration settings.
Step 3: Complete Installation
Finish the Configuration:>>Once the configuration is complete, click "Finish".>>Installation Complete:>>The MySQL installation is now complete. You can open MySQL Workbench to manage your databases or use the MySQL command line.
Step 4: Verify Installation>>Open MySQL Workbench:>>Launch MySQL Workbench from the Start menu or desktop shortcut.>>Connect to MySQL Server:>>Create a new connection using the root account and the password you set during installation.>>Verify Connection:>>If the connection is successful, you should see the MySQL Workbench dashboard.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
