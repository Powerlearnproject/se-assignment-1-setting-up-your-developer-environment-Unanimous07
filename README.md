[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282054&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   have choose to work using windows 10

         Steps involved in installing Windows 10:
      
      Download the Media Creation Tool: Head over to the Microsoft software download website for Windows 10 [download windows 10 ON Microsoft microsoft.com]. Click on "Download tool now" 
            to get the Media Creation Tool.
      
      Run the Media Creation Tool: Double-click the downloaded file to launch the tool. Agree to the license terms and privacy policy.
      
      Create installation media: Choose "Create installation media for another PC" and click "Next." Select the language, edition (Home, Pro, etc.), and architecture (32-bit or 64-bit) 
           of Windows 10 you want to install. Choose "USB flash drive" (recommended) and select your USB drive from the list. The tool will download Windows 10 and create a bootable USB 
           drive.
      
      Boot from the USB drive:  Restart your computer and press the key to enter the boot menu (usually F12, Delete, or Esc - check your motherboard manual for specifics). Select the USB 
            drive as the boot device.
      
      Begin the installation process:  The Windows 10 setup will start. Follow the on-screen instructions, which will guide you through selecting your language, time zone, keyboard 
            layout, agreeing to the license terms, and choosing the type of installation (Upgrade or Custom).
      
      Upgrade vs. Custom install:
      
      Upgrade: This option tries to preserve your existing Windows installation, files, and settings.
   
      Custom: This option completely erases the drive and performs a clean installation of Windows 10. (**Data loss warning! Back up important files beforehand if choosing this option.)
             Follow on-screen prompts:  The installation process will take some time, and your computer might restart several times. The on-screen instructions will guide you through 
             creating a user account, setting up passwords, and configuring Windows settings.
      
      Windows 10 installation complete:  Once the installation is finished, your computer will boot into Windows 10. You might need to go through some additional setup screens to 
            complete the process.

3. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Vscode has been downloaded and installed

      1. Download VS Code:
         
         Head over to the official VS Code download page: [download vscode].
         You'll see options for Windows, macOS, and Linux. Choose the one that matches your operating system.
         
      3. Run the installer:
         
         Once downloaded, double-clicked the installer file (e.g., VSCodeSetup-x64.exe on Windows).
         then Followed the on-screen wizard instructions, which typically involve accepting license agreements and choosing an installation location.

         Windows Specifics:
         By default, VS Code is installed under C:\Users\{Unanimous}\AppData\Local\Programs\Microsoft VS Code.
         You can choose to create a desktop shortcut and integrate VS Code with your file explorer context menu during installation.
         Optional: Manual extraction (Windows and Linux):
         
     
   
5. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   my git is downloaded and install that am able to ull from the repositories and push aswel.

   Windows: Downloaded and install Git for Windows from the official website: [git bash windows download ON Git SCM git-scm.com]

      2. Open a terminal or command prompt:
      
      This is where you'll interact with Git using commands.
   
      3. Initialize a Git repository in your project directory:
      
      Navigated to my project directory using the cd command in your terminal.
      Once there, runed the command git init to create a new Git repository. This createed a hidden folder called .git in my project directory, which stores all the version control 
      information.
      
      4. Configured my username and email (optional but recommended):
      
      These details are used for commit messages to identify who made the changes(me).
      Runned the following commands,:
      git config --global user.name "Kelvin Mulera"
      git config --global user.email "<200100518>"
   
      5. Stage changes for my first commit:
      
      Git tracks changes in my files. Using the git add command to tell Git which files I want to include in my next commit (snapshot of your project's state).
      git add <filename>: Adds a specific file.
      git add .: Adds all tracked files in the current directory.
   
      6. Committing my changes:
      
      Using the git commit command to create a snapshot of the currently staged changes. then this needs fr the provision of a descriptive commit message that summarizes the changes I 
       made.
      git commit -m "<commit message>": Creates a commit with the provided message.
   
      7. (Optional) Track remote repositories (e.g., GitHub):
      
      for collaboration with others or keep backups online, I  connected my local repository to a remote repository service like GitHub. This involves creating a remote 
       repository, adding the remote URL to my local repository, and pushing my commits to the remote repository.

7. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
my environment is now set up with languages like Python, Dart

      Run the downloaded installer:
      Double-clicked the downloaded .exe file (e.g., python-3.12.0-amd64.exe).
   
      3. Configure the installation:
      
      The installer walked me through the setup process. Here's what I looked out for:
      
      
      "Add Python 3.x to PATH" checkbox: It's highly recommended to check this box. This allows me to run Python commands from any directory in my command prompt.
      Other options: You can leave the other options at their defaults unless you have specific requirements.
      Clicked "Install" to begin the installation.
      
      4. Waited for the installation to complete:
      The installation process might take a few minutes depending on your internet speed and system configuration.

      6. Verify the installation (optional):
      Opened a Command Prompt window (search for "cmd" in the Start menu).
      
      Typed python --version and press Enter.
       python-3.12.0 appeared 

9. Install Package Managers:
   If applicable, install package managers like pip (Python).
   Yes the packages have been installed.
   pip is a package that comes with python so there was no need to install it independently. 

11. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   Check mysql downladed and installed.

    Downloaded and Installed MySQL:
      Head over to the official MySQL downloads website as given above
      Downloaded the MySQL Installer for Windows (.msi file) based on your system architecture (32-bit or 64-bit).
      
      2. Run the MySQL Installer:
      Double-clicked the downloaded .msi file to launch the installer.

      4. Choosing the Setup Type:
      The installer offered two main options:
      Typical: This is the recommended option for most users. It performs a standard installation with default settings.
      Custom: This option allows a user to customize various aspects of the installation, like data directory location, network configuration, and security settings. (Recommended for 
      experienced users only).
    
      4. Configuring Settings (if using Custom Setup):
      If you choose the Custom setup, you'll be presented with several configuration options. Here are some key points:
      Port Number: By default, MySQL uses port 3306. You can keep this or change it if needed (ensure firewalls allow connections on this port).
      Root Password: Set a strong password for the root user account. This is crucial for database security.
      Data Directory: This specifies where MySQL stores its data files. You can keep the default location or choose a custom one.
      
      5. Start the MySQL Service:
      During installation, you can choose to start the MySQL service automatically after installation. This ensures the database server is running whenever you need it.
      
      6. Secure the Installation (Important):
      After installation, it's essential to secure your MySQL server. Here are some recommended steps:
      Remove anonymous user access: By default, MySQL allows anonymous connections. Use the mysql_secure_installation script to remove this and set the root password.
      Create user accounts: Create specific user accounts with limited privileges for your applications to access the database instead of using the root account.
      Configure firewalls: Ensure your firewall allows connections to the MySQL port (default: 3306) only from authorized machines.
      
      7. Connecting to the MySQL Server:
      Once the server is running and secured, you can connect to it using the MySQL command-line client or a graphical tool like MySQL Workbench.

13. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

      for the django project am using virtulization, in which i created a virtual environment using a pipenv packege which is much simple compared to virtualenv

15. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
 checked

    just to mention a few on
    Visual Studio Code (VS Code):

      Syntax highlighting: One of the core functionalities of VS Code itself. There are also extensions for specific languages like Python (Pylance) or Java (Java Extension Pack).

     Linting: ESLint for JavaScript/TypeScript, Pylint for Python, etc.
    
      Code formatting: Prettier for various languages, EditorConfig for managing consistent formatting across teams.

     Version control integration: GitLens for advanced Git functionalities within VS Code.
    
17. Document Your Setup:
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
