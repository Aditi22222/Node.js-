# Table of Contents

- [Introduction](#introduction)
- [History](#history)
- [Installation](#installation)
- [Javascript Fundamentals in Node](#Javascript-Fundamentals-in-Node)
- [The Import Function And Variables From Another File](The-Import-Function-And-Variables-From-Another-File)
- [Http Module](#Http-Module)
- [Core Module ](Core-Module)
- [Nodemon Package](Nodemon-Package)
- [API](API)
- [Postman](Postman)
- [Input from cammand line](Input-from-cammand-line)
- [Create file with input](Create-file-with-input)
- [Delete the file with input](Delete-the-file-with-input)
- [Desplay file list from folder](Desplay-file-list-from-folder)


# Introduction to Node.js

- Node.js is an open-source, server-side platform built on Chrome's JavaScript runtime, allowing developers to build scalable network applications.
- It uses an event-driven, non-blocking I/O model, making it lightweight and efficient, suitable for real-time applications with high throughput.
- Node.js enables developers to write server-side code using JavaScript, a language traditionally used for client-side scripting in web browsers.
- It provides a rich ecosystem of libraries and frameworks, known as npm (Node Package Manager), which simplifies the development process by offering reusable modules and tools.
- With Node.js, developers can create a wide range of applications, including web servers, APIs, command-line tools, desktop applications, and more.
- Its popularity continues to grow due to its performance, scalability, and versatility, making it a preferred choice for building modern web applications.

# History of Node.js

- **2009**: Ryan Dahl introduced Node.js, inspired by the need for a scalable server-side solution to handle I/O-bound operations.
- **2010**: Node.js gained attention for its performance and scalability, attracting developers interested in building real-time applications.
- **2011**: The first Node.js package manager, npm, was released, providing a vast ecosystem of modules and tools for developers.
- **2012**: Node.js gained significant adoption, with companies like LinkedIn, Netflix, and PayPal using it to power their applications.
- **2015**: The release of Node.js version 4.0 marked the convergence of the Node.js and io.js codebases, leading to improved collaboration within the Node.js community.
- **2018**: The release of Node.js version 10 introduced long-term support (LTS), ensuring stability and security for enterprise applications.
- **2020**: Node.js continued to evolve, with ongoing updates and enhancements to meet the changing demands of modern web development.

# Installation Process for Node.js

To install Node.js on your computer, follow these steps:

1. **Download Node.js**: Visit the official Node.js website at [nodejs.org](https://nodejs.org) and download the appropriate installer for your operating system (Windows, macOS, or Linux).

   ![Screenshot 2024-03-09 114549](https://github.com/Aditi22222/Node.js-/assets/162342704/6d67d8c3-f46b-4628-be25-667bb6bfe77f)

3. **Run Installer**: Once the download is complete, run the installer and follow the on-screen instructions. Accept the license agreement and choose the installation directory if prompted.

4. **Verify Installation**: After the installation is complete, open a command prompt or terminal window and type the following command to verify that Node.js and npm (Node Package Manager) have been installed successfully:
node -v
npm -v
This command will display the installed version of Node.js and npm, respectively.

![Screenshot 2024-03-09 115031](https://github.com/Aditi22222/Node.js-/assets/162342704/0f7271ca-f7e9-4ae8-866b-18ca9fb39c36)



6. **Test Installation**: To ensure that Node.js is working correctly, create a simple JavaScript file (e.g., `app.js`) with the following code:

![Screenshot 2024-03-09 115406](https://github.com/Aditi22222/Node.js-/assets/162342704/d3e5de49-1ed7-4c56-a64b-2e9741e480d0)

Save the file and run it using Node.js by typing the following command in the terminal.

#Javascript Fundamentals in Node

![Screenshot 2024-03-09 122040](https://github.com/Aditi22222/Node.js-/assets/162342704/2983b408-0822-4217-bd79-d526b406cca0)
![Screenshot 2024-03-09 122156](https://github.com/Aditi22222/Node.js-/assets/162342704/7f6fa3de-93f3-4c4e-86dc-e5016dcda1fd)
![Screenshot 2024-03-09 122315](https://github.com/Aditi22222/Node.js-/assets/162342704/238f1950-bbe9-4f22-b05e-4886309b3038)

#Http Module

![Screenshot 2024-03-11 111721](https://github.com/Aditi22222/Node.js-/assets/162342704/4295380a-defc-4f4e-8e7e-9fecd85a33ff)

![Screenshot 2024-03-11 111731](https://github.com/Aditi22222/Node.js-/assets/162342704/5f446aaf-90bd-4305-a552-fdb3618e1033)

#The Import Function And Variables From Another File
![Screenshot 2024-03-09 123310](https://github.com/Aditi22222/Node.js-/assets/162342704/3fa8d5f0-8213-4612-a890-928c195a93b9)
![Screenshot 2024-03-09 123318](https://github.com/Aditi22222/Node.js-/assets/162342704/6fe4933a-0107-4503-90a1-5d856c049c94)
# Core Module  
![Screenshot 2024-03-11 113746](https://github.com/Aditi22222/Node.js-/assets/162342704/1648955a-b5fa-4c08-8644-f1dd023ef6ca)
# Nodemon Package

![Screenshot 2024-03-11 122059](https://github.com/Aditi22222/Node.js-/assets/162342704/0f74eaf1-74a1-4c18-a97e-09aa260601b3)

![Screenshot 2024-03-11 122140](https://github.com/Aditi22222/Node.js-/assets/162342704/0e376b6d-7623-406e-b28c-3743186643a1)
# API 

![Screenshot 2024-03-11 125303](https://github.com/Aditi22222/Node.js-/assets/162342704/768ae9b0-8d86-475f-9c2c-8fc11cffac88)

![Screenshot 2024-03-11 125314](https://github.com/Aditi22222/Node.js-/assets/162342704/6e06adaf-b6b9-4d0c-9e01-52681e5a5e7a)

# Postman

# Testing Node.js HTTP Server with Postman

## Using Postman to Test the HTTP Server

### 1. Start the Node.js server
Ensure that the Node.js server created in the program is running. If not, start the server using the command `node your_server_file.js`.

### 2. Open Postman
Launch the Postman application on your system. If you don't have Postman installed, you can download it from [here](https://www.postman.com/downloads/).

### 3. Create a new request
Click on the "New" button in Postman to create a new request.

### 4. Set request details
- Choose the HTTP method "GET" from the dropdown menu.
- Enter the URL `http://localhost:5000` in the address bar. Adjust the port number if your server is running on a different port.

### 5. Send the request
Click on the "Send" button to send the request to the Node.js server.

### 6. Inspect the response
- Postman will display the response received from the server in the response body section.
- Verify that the response contains JSON data with information about Aditi Singh.



![Screenshot 2024-03-11 152626](https://github.com/Aditi22222/Node.js-/assets/162342704/3c50eb54-0299-43d2-ae10-db1bf154740e)

![Screenshot 2024-03-11 152637](https://github.com/Aditi22222/Node.js-/assets/162342704/c3a956ea-f8bc-40db-9b7f-4e18b0055a2e)

![Screenshot 2024-03-11 152654](https://github.com/Aditi22222/Node.js-/assets/162342704/8e71be5c-edb7-489f-a9b4-331639384cde)

# Input from cammand line

![Screenshot 2024-03-12 102833](https://github.com/Aditi22222/Node.js-/assets/162342704/d7ae692a-d94b-48c0-af76-996327fefd19)

# Create file with input

- The script utilizes Node.js's built-in `fs` module for file system operations.
- It accesses command line arguments using `process.argv`.
- If the third argument (`input[2]`) is `'add'`, it writes the content provided as the fourth argument (`input[4]`) to the file specified as the third argument (`input[3]`).
- If the third argument is `'remove'`, it removes the file specified as the third argument (`input[3]`).
- If the third argument is neither `'add'` nor `'remove'`, it prints "Invalid input" to the console.


![Screenshot 2024-03-12 105117](https://github.com/Aditi22222/Node.js-/assets/162342704/08cc5850-4d90-4911-85f3-ff8c19885639)

# Delete the file with input

![Screenshot 2024-03-12 110527](https://github.com/Aditi22222/Node.js-/assets/162342704/763abc18-35c1-47c8-af51-ac30de6f790f)

# Desplay file list from folder

![Screenshot 2024-03-12 131713](https://github.com/Aditi22222/Node.js-/assets/162342704/da33b225-57e9-4494-9fc0-a8ba611129ff)
