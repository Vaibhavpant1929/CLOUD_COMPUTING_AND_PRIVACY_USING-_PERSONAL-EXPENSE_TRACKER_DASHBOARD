# CLOUD_COMPUTING_AND_PRIVACY_USING_PERSONAL_EXPENSE_TRACKER_DASHBOARD
FIRST STEP :-
The project begins by setting up a cloud infrastructure. I logged into my AWS account to leverage its robust services for hosting, data storage, and security. AWS provides the backbone for ensuring scalability, reliability, and secure handling of sensitive expense data.

SECOND STEP:-
Navigate to the EC2 Instance
Once logged into my AWS account, I proceeded to the EC2 Dashboard by selecting the EC2 service from the AWS Management Console. The EC2 (Elastic Compute Cloud) service provides scalable virtual servers in the cloud.
In this step, I reviewed the available instances and either launched a new EC2 instance or accessed an existing one. The EC2 instance serves as the core environment for deploying the backend of the personal expense tracker. It provides the necessary computational power and security configurations to process and store sensitive financial data efficiently.
This step is critical because the EC2 instance ensures reliable operations, high availability, and a secure platform for the expense tracker, aligning with the privacy requirements of the project.

THIRD STEP :-
Deploy a Windows Server on EC2 (Free Tier)
After navigating to the EC2 dashboard, I deployed a Windows Server instance on EC2. To optimize costs, I utilized the AWS Free Tier, which allows running certain services at no cost for a limited period.
During this step, I selected a Windows Server AMI (Amazon Machine Image) that fits within the Free Tier specifications, chose the appropriate instance type (t2.micro), and configured the instance settings. This Windows Server serves as the platform for hosting the backend application and database of the personal expense tracker.
By leveraging the Free Tier, this approach ensures a cost-effective deployment while maintaining the project's functionality and privacy-focused architecture.

FORTH STEP:-
Download and Install XAMPP
To set up a local development environment for testing and debugging, I downloaded and installed XAMPP, an open-source web server solution that includes Apache, MySQL, PHP, and Perl.
Visit the Official XAMPP Website:-
I navigated to the official XAMPP website (https://www.apachefriends.org) to ensure I downloaded the latest and most secure version of the software.
Choose the Correct Version:-
Based on the operating system (Windows in this case), I selected the appropriate XAMPP version that supports the required PHP and MySQL versions for the project.
Download the Installer:-
I clicked on the "Download" button for the selected version and saved the installer file to my computer.
Run the Installer:-
Once the download was complete, I opened the installer file and followed the on-screen instructions to install XAMPP. During the installation process, I selected the necessary components such as Apache and MySQL while leaving optional components unchecked.
Complete the Installation:-
After the installation was finished, I started the XAMPP Control Panel to verify that Apache and MySQL services were running correctly.

FIFTH STEP:-
Host the Website in XAMPP (Using the htdocs Directory)
After setting up XAMPP, I hosted the website locally by placing the project files in the htdocs directory, which is the default root folder for XAMPP's Apache server.
Prepare the Project Files:-
I organized the website files, including HTML, CSS, JavaScript, and PHP scripts, into a structured folder to ensure all dependencies and assets were properly linked.
Locate the htdocs Directory:-
The htdocs folder is located within the XAMPP installation directory (e.g., C:\xampp\htdocs). I accessed this directory to place the project files for hosting.
Move the Website Files:-
I copied the entire folder containing the website files and pasted it into the htdocs directory. The folder's name becomes part of the URL used to access the website locally.
Start Apache Service:-
Using the XAMPP Control Panel, I started the Apache service, which acts as the local web server. This step ensures the project can be accessed in a browser.
Access the Website:-
I opened a web browser and entered http://localhost/<folder_name> in the address bar, where <folder_name> is the name of the folder placed in htdocs. This loaded the website, allowing me to test its functionality in a local environment.
