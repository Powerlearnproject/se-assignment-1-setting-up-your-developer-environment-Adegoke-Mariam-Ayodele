[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15254821&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Answer:
   Step by step processes on Installation of Windows Operating System are:-

   Step 1: Prepare Your System
   a) Ensure your computer meets the minimum system requirements for the Windows version you want to install.
   b) Back up all important data as the installation process will format your hard drive.
   c) Create a bootable USB or DVD using the Windows Media Creation Tool.
   
   Step 2: Enter the BIOS
   a) Restart your computer.
   b) Press the specified key (e.g., F1, F2, Del) to access the BIOS setup menu.
   
   Step 3: Set Boot Order
   a) Find the "Boot Order" or "Boot Options" menu.
   b) Set the USB or DVD drive as the first boot device.
   
   Step 4: Start the Windows Installer
   a) Save the BIOS settings and exit.
   b) The computer will restart and boot from the USB or DVD.
   c) You will see the Windows Setup screen.
   
   Step 5: Language and Region Selection
   a) Select the language, time and currency format, and keyboard layout.
   
   Step 6: Install Now and Product Key
   a) Click "Install Now."
   b) If prompted, enter the Windows product key. If you don't have one, you can Skip for now and enter it later.
   
   Step 7: License Agreement
   a) Read and accept the Microsoft Software License Agreement.
   
   Step 8: Choose Installation Type
   a) Select "Custom: Install Windows only (advanced)."
   
   Step 9: Partition and Format Hard Drive
   a) Delete all existing partitions on the target hard drive.
   b) Create a new partition for Windows and format it as NTFS.
   
   Step 10: Begin Installation
   a) Windows will begin copying files and installing.
   b) The installation process may take some time.
   
   Step 11: User Account Setup
   a) Create a new user account with a username and password.
   
   Step 12: Network and Settings
   a) Choose your Wi-Fi network and connect to it.
   b) Customize your privacy settings and Cortana preferences.
   
   Step 13: Finish Installation
   a) Windows will complete the installation and restart the computer.
   b) You will now have a freshly installed Windows operating system.
   
   Additional Tips:
   i) Disconnect non-essential peripherals during installation.
   ii) Ensure you have a stable internet connection if downloading updates during installation.
   iii) If you encounter any errors, search for solutions online or contact Microsoft support.


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   Answer:
   Step by step processes on Installation of Visual Studio Code are:-

   Step 1: Download the Installer
   a) Visit the official Visual Studio Code website: https://code.visualstudio.com/
   b) Click on the "Download" button and select the installer for your operating system (Windows, macOS, or Linux).
   
   Step 2: Run the Installer
   a) Double-click on the downloaded installer file.
   b) Follow the on-screen instructions to install Visual Studio Code.
   
   Windows:
   a) Accept the license agreement.
   b) Choose the installation location.
   c) Select the components you want to install.
   d) Click "Install".
   
   macOS:
   a) Drag and drop the Visual Studio Code icon into the "Applications" folder.
   
   Linux:
   a) Open a terminal window.
   b) Navigate to the directory where you downloaded the installer.
   c) Run the following command:
   
   "sudo dpkg -i [installer_file_name].deb"
   
   Step 3: Launch Visual Studio Code
   a) Click on the Visual Studio Code icon in the Start menu (Windows) or Applications folder (macOS/Linux).
   b) Visual Studio Code will open.
   
   Step 4: Install Extensions
   a) Click on the "Extensions" icon in the left sidebar.
   b) Use the search bar to find and install extensions that add additional functionality to Visual Studio Code.
   
   Step 5: Configure Settings
   a) Click on the "Settings" icon in the left sidebar.
   b) Adjust settings to customize the appearance, behavior, and keyboard shortcuts of Visual Studio Code.
   
   Step 6: Create a Project
   a) Create a new folder for your project.
   b) Open Visual Studio Code and navigate to the project folder.
   c) Click on the "File" menu and select "New" > "Project".
   d) Select a project template or create a new project from scratch.
   
   Step 7: Start Coding
   a) Open a file in the project folder and start writing code.
   b) Visual Studio Code provides code completion, error checking, and other features to help you develop.
   
   Additional Tips:
   i) Install version control software (e.g., Git) and configure it with Visual Studio Code for version control integration.
   ii) Explore the vast community of extensions to enhance your development workflow.
   iii) Refer to the Visual Studio Code documentation for more detailed information and tutorials: https://docs.microsoft.com/en-us/visualstudiocode/
   

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Answer:
   Step by step processes on Installation and configuration of Git are:-

   Step 1: Install Git
   a) Windows: Download the Git for Windows installer from https://git-scm.com/downloads and follow the installation wizard.
   b) macOS: Use Homebrew to install Git:
   
   "brew install git"
   c) Linux: Use your package manager to install Git:
   i) Debian/Ubuntu:
   "sudo apt install git"
   
   ii) CentOS/Red Hat:
   "sudo yum install git"
   
   iii) Arch Linux:
   "sudo pacman -S git"
   
   Step 2: Configure Git
   Open a terminal or command prompt.
   Set your username and email address for Git:
   
   git config --global user.name "Your Name"
   git config --global user.email "your_email@example.com"
   
   Step 3: Install a Git GUI (Optional)
   a) Consider installing a Git GUI such as GitHub Desktop (https://desktop.github.com/) or GitKraken (https://www.gitkraken.com/) for easier graphical interface.
   
   Step 4: Create a Git Repository
   a) Navigate to the directory where you want to create a Git repository.
   b) Initialize an empty repository:
   
   "git init"
   
   Step 5: Add and Commit Changes
   a) Add files to the staging area (index):
   
   "git add ."
   
   b) Commit the changes with a message:
   
   git commit -m "Initial commit"
   
   Step 6: Link to a Remote Repository (Optional)
   a) If you want your Git repository to be synchronized with a remote server (e.g., GitHub), create a remote repository and link it to your local repository:
   
   "git remote add origin https://github.com/username/repository"
   
   Step 7: Push Changes to Remote Repository (Optional)
   a) After making changes, push them to the remote repository:
   
   "git push origin master"
   (replace "master" with the appropriate branch name)
   
   Additional Tips:
   
   a) Use
   "git status"
   to check the status of your working tree.
   b) Use
   "git diff"
   to compare changes between commits.
   
   c) Use
   "git log"
   to view the history of commits.
   
   d) Use
   "git branch"
   to manage branches in your repository.
   
   e) Use
   "git merge"
   to merge changes from different branches.


4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Answer:
  Step by step processes on Installation of Python are:-

  Step 1: Download the Python Installer
  a) Visit the official Python download page: https://www.python.org/downloads/
  b) Select the version you want to install and choose the appropriate installer for your operating system.
  
  Step 2: Run the Installer
  a) Double-click on the downloaded installer file.
  b) Follow the on-screen instructions to complete the installation process.
  c) Ensure that you select the "Add Python 3.x to PATH" option during installation to add Python to your system path.
  
  Step 3: Verify Installation
  a) Open a command prompt or terminal window.
  b) Type "python" and press Enter.
  c) You should see the Python interactive shell.
  
  Step 4: Install pip (Optional but Recommended)
  a) pip is the package installer for Python.
  b) Type the following command in the command prompt:
  
  "python -m ensurepip --upgrade"

  c) If prompted, install or upgrade pip by following the on-screen instructions.
  
  Step 5: Install Virtual Environment (Optional but Recommended)
  a) A virtual environment creates an isolated Python environment with its own set of packages and dependencies.
  b) Install virtualenv using pip:
  
  "pip install virtualenv"
  
  c) Create a virtual environment:
  
  "virtualenv my_env"
  
  d) Activate the virtual environment:
  
  "source my_env/bin/activate"
  
  e) You can now install packages within the virtual environment:
  
  "pip install <package_name>"
  
  Step 6: Package Management with pip
  a) pip can be used to install, upgrade, remove, and list installed Python packages.
  b) To install a package, use:
  
  "pip install <package_name>"
  
  c) To upgrade a package, use:
  
  "pip install --upgrade <package_name>"
  
  d) To remove a package, use:
  
  "pip uninstall <package_name>"
  
  e) To list installed packages, use:
  
  "pip list"
  
  Step 7: Deactivating Virtual Environment (Optional)
  a) To deactivate the virtual environment, type:
  
  "deactivate"
  
  b) This will return you to the base Python environment.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Answer:
   Step by step processes on Installation of pip (Python) are:-

   Step 1: Check if pip is already installed
   a) Open your terminal or command prompt and type the following command:
   
   "pip -V"
   
   b) If pip is installed, it will display the version number. If not, proceed to the next step.
   
   Step 2: Install get-pip.py
   a) Download the get-pip.py script from the Python Package Index (PyPI):
   
   "curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py"
   
   Step 3: Install pip using get-pip.py
   a) Run the following command to install pip using the downloaded script:
   
   "python get-pip.py"
   
   Step 4: Verify installation
   a) After the installation is complete, check if pip is now installed by running:
   
   "pip -V"
   
   b) You should now see the version number of pip displayed.
   
   Step 5: Upgrade pip (optional)
   a) To ensure you have the latest version of pip, you can upgrade it with the following command:
   
   "pip install --upgrade pip"
   
   Additional Notes:
   i) On macOS using Homebrew, you can install pip with:
   
   "brew install python"
   
   ii) On Windows, make sure Python is added to the PATH environment variable.
   iii) If you encounter errors during installation, consult the official pip documentation.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Answer:
   Step by step processes on Installation of MySQL Database are:-
   
   Step 1: Download MySQL Installer
   a) Visit the official MySQL website: https://dev.mysql.com/downloads/
   b) Choose the appropriate version and operating system.
   c) Click on "Download" to save the installer file.
   
   Step 2: Run the Installer
   a) Navigate to the downloaded file and double-click on it to start the installation wizard.
   b) Follow the on-screen prompts to choose the installation type (e.g., Developer Default).
   
   Step 3: Select Components
   a) Select the MySQL components you need to install, such as the MySQL Server, MySQL Workbench, or other tools.
   b) You can also choose to install the MySQL Connector for your preferred programming language.
   
   Step 4: Configure Server Settings
   a) Enter the root password for your MySQL server.
   b) Choose the server connection type (e.g., TCP/IP) and port number (default: 3306).
   c) Optionally, you can enable additional features like SSL encryption.
   
   Step 5: Execute Installation
   a) Click on "Install" to begin the installation process.
   b) The installer will download and install the necessary files.
   c) Once complete, click on "Finish" to close the wizard.
   
   Step 6: Start MySQL Server
   a) Open the MySQL Command Line Interface (CLI) tool (e.g., mysql.exe on Windows).
   b) Connect to the server using the root password you set during installation:
   
   "mysql -u root -p"
   
   Step 7: Create a Database
   a) Once connected to the server, create a new database using the following command:
   
   "CREATE DATABASE <database_name>;"
   
   Replace
   
   "<database_name>"
   
   with the name of your new database.
   
   Additional Tips:
   i) Ensure you have sufficient disk space and RAM for the MySQL installation.
   ii) Consider creating a non-root user with limited privileges for everyday operations.
   iii) Regularly back up your MySQL data to prevent data loss.
   iv) Keep MySQL updated with the latest security patches.


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
