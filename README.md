# **Linux-Fundamentals**
Excelling in today's tech fields like DevOps, Cloud Computing, Software Development, Cybersecurity, Data Analysis/Science, AI, and QA Testing starts with the basics. This project focuses on Linux, providing the fundamental understanding crucial for any aspiring tech professional.


## **Project Overview** 

Embark on a practical journey to master AWS EC2 instance management, starting with an Ubuntu Linux foundation. This project covers everything from bringing an EC2 instance online and securely connecting with MobaXterm, to performing essential Linux tasks and establishing a functional web server using Nginx. Clear, step-by-step instructions are paired with visual aids for optimal understanding.

### **Three Steps to Embark on this Cloud project:**

### **Step 1: Cloud Infrastructure & Operating System Foundation**

- **AWS EC2:** Begin by leveraging this cloud computing service to provision and launch your virtual server. This forms the foundational infrastructure for the project.

- **Ubuntu:** Select and deploy this popular Linux distribution as the robust operating system for EC2 instance, providing the environment for all subsequent configurations.

**_Here are explanations for each sub-step:_**

**i.AWS Account Creation**
***:*** This initial step is crucial for gaining the necessary permissions and access to AWS services, allowing you to begin provisioning cloud resources.

An AWS account is fundamental as it grants immediate access to provision and manage diverse cloud resources, including remote servers (like EC2 instances). This access is essential for secure operations, and gaining practical experience within the vast AWS ecosystem.
<img width="1920" height="953" alt="1 AWSACCCreation" src="https://github.com/user-attachments/assets/01e29527-b7db-42cd-ab31-4d141ba86610" />



**ii.Signing in to AWS**
***:*** This view helps confirm that you are within the EC2 dashboard and provides an overview of any existing instances, setting the stage for launching a new one.

<img width="1905" height="953" alt="2 AWSSignin" src="https://github.com/user-attachments/assets/0b6f2cd5-227f-4211-8419-d49b6788968d" />



**iii.AWS Console Home**
***:*** Familiarizing yourself with the AWS Console Home is important as it serves as the central dashboard for navigating various AWS services and monitoring your resources.

<img width="1891" height="598" alt="3 AWS MGT Console" src="https://github.com/user-attachments/assets/0c6a2cac-9b56-4e7f-acf2-24a768df7629" />



**iv.EC2 Instance in View**
***:*** This view helps confirm that you are within the EC2 dashboard and provides an overview of any existing instances, setting the stage for launching a new one.

<img width="1905" height="809" alt="4 ECS Instances In View" src="https://github.com/user-attachments/assets/559bfd9f-0742-4a27-9cb4-df535b7c6856" />



**v.Navigating to EC2 Instance Service**
***:*** Directly navigating to the EC2 service ensures you are in the correct section to initiate the instance creation process.

<img width="1909" height="949" alt="5 Navigating to EC2 Service" src="https://github.com/user-attachments/assets/bdd801de-b7ea-4420-979c-55b9a99d6c5a" />



**vi.Launching An EC2 Instance**
***:*** This is the primary action to begin configuring and deploying a new virtual server (EC2 instance) in the cloud.

<img width="1881" height="908" alt="6 Launching An EC2 Instance" src="https://github.com/user-attachments/assets/34c3d101-0e77-4384-9bc7-e3290856a9a5" />



**vii.Instance Server Naming And OS Selection**
***:*** Naming your instance clearly aids in identification and management, while selecting the Ubuntu OS provides a stable and widely used Linux environment for the project.

<img width="1910" height="933" alt="7 Instance Server Naming and Select OS" src="https://github.com/user-attachments/assets/e6df21d1-ce64-44f2-8d5d-da11d785d8e4" />



**viii.AMI Selection And Instance Type**
***:*** Choosing the right Amazon Machine Image (AMI) determines the software pre-installed on your instance, and selecting an instance type defines its hardware specifications (CPU, memory), impacting performance and cost

<img width="1900" height="1040" alt="8 AMI Selection and Instance Type" src="https://github.com/user-attachments/assets/b42687aa-6bbb-495a-a33e-883f004ca34b" />



**ix.Creating New Key Pair**
***:*** A key pair (private and public key) is essential for securely connecting to your EC2 instance via SSH, providing cryptographic authentication and preventing unauthorized access.

<img width="1899" height="1040" alt="9 Create New Key Pair" src="https://github.com/user-attachments/assets/7143ae82-f9eb-49d9-8f5e-fa8262a54978" />



**x.Network And Storage Configuration**
***:*** Configuring network settings (like security groups for firewall rules) and storage (EBS volumes) ensures your instance is accessible and has sufficient space for its operations.

<img width="1896" height="1040" alt="10 Network and storage congiguration" src="https://github.com/user-attachments/assets/04d01a17-9c07-4379-9cff-545e9f37e19a" />



**xi.Connecting EC2 Instance**
***:*** This step outlines the methods available for establishing a connection to your newly launched EC2 instance, typically via SSH.

<img width="1365" height="928" alt="10 Connect Instance" src="https://github.com/user-attachments/assets/b5d2668c-0244-46d6-87eb-ea8db654e093" />



**xii.EC2 Instance Launched And Running**
***:*** Confirming the instance is in a "running" state signifies that the virtual server is provisioned and ready for use, allowing you to proceed with remote access.

<img width="1919" height="1018" alt="11 Instance Launched And Running" src="https://github.com/user-attachments/assets/8bbf6648-96e7-46ea-8a89-ae154dd35235" />




### **Step 2: Secure Access & Core System Management**

- **MobaXterm:** Establish a secure and efficient connection to newly launched EC2 instance using this versatile terminal emulator for SSH.

- **Linux Commands:** Master essential command-line tools like apt (for package management), tree (for directory visualization), and systemctl (for service management) to effectively administer and interact with your Ubuntu system.

**_Here are explanations for each sub-step:_** 


**xiii.Downloading MobaXterm For SSH Connection On Window OS**
***:*** MobaXterm provides a robust and user-friendly interface for SSH, making it an ideal choice for Windows users to connect to and manage their Linux instances.

<img width="1364" height="1017" alt="12 Downloading MobaXterm For SSH Connection On Window OS" src="https://github.com/user-attachments/assets/89e89881-9db7-41e4-a7df-12e09fa21b07" />



**xiv.MobaXterm Home Edition Selection**
***:*** Selecting the Home Edition is sufficient for personal projects and provides all necessary features for this guide's purposes without requiring a license.

<img width="1364" height="1017" alt="12 Downloading MobaXterm For SSH Connection On Window OS" src="https://github.com/user-attachments/assets/14b7e052-ba0c-4416-94bf-f9827797dd68" />



**xv.MobaXterm Download Launch**
***:*** Initiating the download prepares the client software needed to establish a secure shell connection to your remote server.

<img width="1294" height="832" alt="14 MobaXterm Download Launch" src="https://github.com/user-attachments/assets/e719568b-5ceb-48fc-ac9d-6de364dbb15e" />



**xvi.Starting Terminal**
***:*** Opening a local terminal within MobaXterm provides the command-line interface necessary to execute the SSH command and connect to the EC2 instance.

<img width="1111" height="653" alt="15 Starting Terminal" src="https://github.com/user-attachments/assets/4dc838db-ae65-4995-84d4-c02cc250d633" />



**xvii.Navigating To Download For Key Pair File**
***:*** Locating your downloaded `.pem` key pair file is critical as it's required by SSH for authenticating your connection to the EC2 instance.

<img width="1473" height="795" alt="16 Navigating to Download For Key Pair" src="https://github.com/user-attachments/assets/b5373f2c-44f7-422c-9aa7-aadbfaf404df" />



**xviii.Copying Instance Public IP**
***:*** The public IP address of your EC2 instance is the unique network address used by the SSH client to locate and connect to your virtual server over the internet.

<img width="1920" height="1024" alt="17 Coping Instance Public IP" src="https://github.com/user-attachments/assets/0268a107-181b-4ee0-a7cd-716dea1ec1b5" />



**xix.Running SSH Command**
***:*** Executing the SSH command with the correct key pair and instance details initiates the secure encrypted connection to your remote Linux server.

<img width="1472" height="631" alt="18 Running SSH Command" src="https://github.com/user-attachments/assets/2c32814a-8906-49cb-97c7-629484a1130b" />



**xx.Remote Server Connection Successful**
***:*** This visual confirmation verifies that you have successfully established a secure terminal session with your EC2 instance, allowing you to begin interacting with the Linux operating system.

<img width="1094" height="690" alt="19 Remote Server Connection Successfully Established" src="https://github.com/user-attachments/assets/0043e26a-7d54-49b4-a1f3-572fa44e699e" />



**xxi.Checking Hostname And Apt Update**
***:*** Checking the hostname confirms you're on the correct server, and running `sudo apt update` refreshes the package lists, ensuring you can install the latest versions of software.

<img width="1094" height="653" alt="20 Checking Hostname And Apt Update" src="https://github.com/user-attachments/assets/1b13cbe4-8bb0-42b6-98ea-83594adcb854" />
<img width="1094" height="653" alt="21 HostnameAptUpdate" src="https://github.com/user-attachments/assets/f28b47e9-4def-4572-b430-d6d7529041ef" />



**xxii.Installing Software Package Called Tree**
***:*** Installing the `tree` package demonstrates basic package management `(apt install)` and provides a utility to visually display directory structures, which is useful for file system navigation

<img width="1094" height="690" alt="22 Installing Software Package Called Tree" src="https://github.com/user-attachments/assets/42fa098c-fc3d-44b2-b521-4df44b9c1a39" />



**xxiii.Verifying The Installation Of Tree**
***:*** Verifying the installation `(tree -v)` confirms that the package was successfully added to your system and is ready for use, ensuring the integrity of your setup.

<img width="1094" height="653" alt="23 Verifying the installation of Tree" src="https://github.com/user-attachments/assets/72dde303-5357-4f7f-9a9a-2226da520203" />



**xxiv.Updating Installed Package**
***:*** Running ( ' )`sudo apt upgrade`( ' ) is essential for applying updates to all installed packages, enhancing security and stability by fixing bugs and introducing new features.

<img width="1094" height="677" alt="24 Upgrading Installed Package" src="https://github.com/user-attachments/assets/0f835146-35bf-4003-8ab6-3056c40706ed" />



**xxv.Removing Installed Software**
***:*** This step demonstrates how to safely remove software ```(sudo apt remove --purge)``` and its associated configuration files, which is crucial for managing disk space and system cleanliness.

<img width="1094" height="686" alt="25 Removing Installed Software" src="https://github.com/user-attachments/assets/c84b7983-af81-4d2f-b3d4-a458c2a0734f" />




### **Step 3: Web Server Deployment & Application Hosting**

- **Nginx:** Install and configure this lightweight, high-performance web server on your EC2 instance. This will enable you to host a default webpage, making your instance accessible via the internet.

**_Here are explanations for each sub-step:_**


**xxvi.Installing Nginx**
***:*** Installing Nginx ```(sudo apt install nginx)``` transforms your EC2 instance into a web server, capable of serving web content and making it publicly accessible.

<img width="1094" height="680" alt="26 Installation of Nginx" src="https://github.com/user-attachments/assets/31cd2a8b-d6ca-46d9-b420-fa23547d2e26" />



**xxvii.Verifying Installation of Nginx And Version**
***:*** Checking the Nginx service status and version ensures that the web server is running correctly and confirms its successful installation, a prerequisite for hosting content.

<img width="1094" height="681" alt="27 Verifying Nginx Installation and Version" src="https://github.com/user-attachments/assets/cc9c9808-24c5-4b26-95b6-b6fb4c0afd46" />



**xxviii.Uninstalling Nginx And Any Binaries or Dependencies Left Behind**
***:***  This final cleanup step demonstrates proper uninstallation ```(sudo apt autoremove --purge nginx)``` to remove Nginx and any unused dependencies, maintaining a tidy system.

<img width="1094" height="682" alt="28 Uninstalling Nginx And Any Binaries or Dependencies Left Behind" src="https://github.com/user-attachments/assets/628afc6f-f7f2-42ae-9d10-d7ae258924fe" />




















