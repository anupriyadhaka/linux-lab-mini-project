# linux-lab-mini-project
Introduction:  Hosting a static website on Linux involves installing and configuring a web server (like Apache) to serve HTML pages to users through a browser. A static website contains fixed HTML, CSS, and image files that are the same for all users.


### UNIVERSITY INSTITUTE OF COMPUTING

PROJECT REPORT
--------------

### ON

**Hosting a Static Website on Linux**

**Program Name:** BCA**Subject:** Linux Administration Lab**Code:** 23CAP-305

**SUBMITTED BY:****Name:** Anupriya Dhaka  **UID:** 23BCA10808**Branch:** BCA  **Section/Group:** 23BCA-9(B)**Semester:** 5th  **Date of Submission:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

**SUBMITTED TO:****Name:** Rajat Kapoor  **Date of Submission:** 06-11-2025**Designation:** Assistant Professor  **Sign:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

BONAFIDE CERTIFICATE
--------------------

Certified that this project report “**Hosting a Static Website on Linux**” is the bonafide work of **Anupriya Dhaka (UID: 23BCA10808)** who carried out the project work under my supervision.

………………………………………**Signature****UIC Department****Assistant Professor****Rajat Kapoor**

Linux Administration Lab
------------------------

### Project-Based Learning Report

### Title: Hosting a Static Website on Linux

### 1\. Aim of the Project:

To understand and implement the process of **hosting a static website on a Linux server** using the **Apache web server**.The project aims to help students learn how to configure, deploy, and access a website from a Linux environment.

### 2\. Performing Task:

#### **Introduction:**

Hosting a static website on Linux involves installing and configuring a **web server (like Apache)** to serve HTML pages to users through a browser.A static website contains fixed HTML, CSS, and image files that are the same for all users.

#### **Objectives:**

*   To install and configure the Apache web server on Linux.
    
*   To create and host a basic HTML web page.
    
*   To understand the structure of Linux web directories.
    
*   To test website accessibility via the localhost or IP address.
    
*   To gain hands-on experience in basic web hosting using Linux commands.
    

#### **Tools and Technologies Used:**

*   **Operating System:** Ubuntu Linux
    
*   **Web Server:** Apache2
    
*   **Commands/Tools:** apt, systemctl, nano, chmod, ufw, curl
    
*   **Shell:** Bash Terminal
    

### 3\. Steps Included:

**S1)** Update system packages using: sudo apt update**S2)** Install the Apache web server: sudo apt install apache2 -y**S3)** Start and enable Apache service:

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   sudo systemctl start apache2    sudo systemctl enable apache2   `

**S4)** Verify Apache server status: sudo systemctl status apache2**S5)** Open a web browser and visit http://localhost to check default Apache page.**S6)** Navigate to the web root directory: cd /var/www/html**S7)** Create or edit index.html using: sudo nano index.html**S8)** Add your HTML content and save the file.**S9)** Refresh the browser to view your custom web page.

### 4\. Algorithm / Logic / Flow Chart

*   Start the Ubuntu system.
    
*   Open terminal and update system packages.
    
*   Install Apache web server.
    
*   Start and enable Apache service.
    
*   Create a simple HTML file in /var/www/html.
    
*   Access the hosted page using a web browser (localhost).
    
*   Verify the output and ensure the site loads correctly.
    
*   Stop the server after testing (optional).
    

### 5\. Code Overview

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   # Update system  sudo apt update  # Install Apache web server  sudo apt install apache2 -y  # Start and enable Apache  sudo systemctl start apache2  sudo systemctl enable apache2  # Verify Apache status  sudo systemctl status apache2  # Create custom HTML file  cd /var/www/html  sudo nano index.html   `

**Sample HTML Code:**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   My Static Website  Welcome to My Website Hosted on Linux! ======================================  This page is hosted using the Apache web server on Ubuntu.   `

**Access the website:**

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   http://localhost   `

### 6\. Output: (Screenshots)

*   Screenshot of Apache installation command
    
*   Screenshot of http://localhost default Apache page
    
*   Screenshot of your custom web page displayed in the browser
    
*   Screenshot of terminal showing Apache running (sudo systemctl status apache2)
    

### 7\. Conclusion:

This project demonstrated how to **host a static website using Apache on Linux**.By completing the setup, students learned how to install web server software, manage web directories, and test hosted pages.It provided real-world knowledge of Linux web hosting and server configuration.

### 8\. Learning Outcomes:

1.  Learned how to install and configure Apache web server.
    
2.  Understood how static websites are hosted on Linux.
    
3.  Gained knowledge of Linux directory structure for web hosting.
    
4.  Learned basic HTML page deployment.
