# AWS EC2 Ubuntu Apache Web Server Setup with Customized Content


Certainly! This project involves setting up a basic web server on an AWS EC2 instance using Ubuntu and Apache. Here's a detailed breakdown:

1. **Launch an EC2 Instance:**
   - You initiate a new EC2 instance on AWS, selecting the Ubuntu image.

2. **Connect to EC2 Instance through EC2 Instance Connect:**
   - You establish a secure connection to the EC2 instance using EC2 Instance Connect.

3. **Install Apache Web Server:**
   - Update and upgrade the packages on the Ubuntu server to ensure everything is current.
   - Install the Apache2 web server using the package manager.

4. **Check Apache Installation:**
   - Verify if Apache is installed correctly by running `which apache2` or `apache2 -v`.

5. **Start Apache Service:**
   - Start the Apache service on the server.

6. **Check Apache Service Status:**
   - Confirm the status of the Apache service.

7. **View Default Apache Page:**
   - Use the public IP address of the EC2 instance in a browser to check if Apache is running. This should display a default Apache welcome page.

8. **Customize Default Page:**
   - Navigate to the directory where web content is stored (`/var/www/html`).
   - Remove the default `index.html` file.
   - Create and edit a new `index.html` file with your own content.

9. **Restart Apache Service:**
   - Restart the Apache service to apply changes.

10. **View Customized Page:**
    - Use the public IP address again in the browser to see your customized website content.

This project essentially guides you through the process of setting up a basic web server on an AWS EC2 instance, installing Apache, and customizing the default web page with your own content. It's a fundamental exercise in deploying a web server and serves as a starting point for more advanced web development and server management tasks.