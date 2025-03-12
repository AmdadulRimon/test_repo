# Portfolio Website for Thumbnail Designers

## Project Description 

This is an open-source portfolio platform designed specifically for thumbnail designers to showcase their creative work, connect with clients, and build their professional identity. This project provides a modern, customizable, and responsive website template that allows designers to highlight their best projects, share their design process, and establish meaningful connections with potential collaborators or clients.

## Table of Contents

- [Project Description](#project-description)
- [Install the Project](#install-the-project)
  - [Install Git](#install-git)
  - [Install Node.js](#install-nodejs)
  - [Install Visual Studio Code](#install-visual-studio-code)
- [Get Started](#get-started)
  - [Install Process](#install-process)
  - [Run Process](#run-process)
- [How You Can Customize the Site](#how-you-can-customize-the-site)

## Install the Project

To get started with the portfolio website, you need to clone this repository and install the necessary dependencies. If you're not familiar with Git or Node.js, follow the steps below.

### Install Git

Git is a tool for downloading the project from GitHub. If you don’t have Git installed, here’s how you can get it:

1. **Download Git**: Go to the [Git download page](https://git-scm.com/downloads).
2. **Install Git**: Follow the instructions for your operating system (Windows, macOS, or Linux).
   - On Windows, run the installer and select the default settings.
   - On macOS, you may need to install Homebrew first and use `brew install git`.

    After installation, verify that Git is installed by opening a terminal (or Git Bash on Windows) and typing:
     
    ```bash
    git --version
    ```

If you see a version number, Git is installed correctly.

### Install Node.js

Node.js is required to run the website locally. It also helps to manage project dependencies.

1. **Download Node.js**: Go to the [Node.js download page](https://nodejs.org/en/).

2. **Install Node.js**: Download the latest LTS version and follow the installation instructions for your operating system.

   After installation, verify that Node.js is installed by opening a terminal (or Command Prompt on Windows) and typing:

    ```bash
    node --version
    ```

    You should see a version number. Next, check if npm (Node's package manager) is installed by typing:

    ```bash
    npm --version
    ```

If both commands return version numbers, Node.js is set up correctly.

### Install Visual Studio Code

Visual Studio Code (VS Code) is a popular code editor that is highly recommended for editing and managing your project files. Follow these steps to install VS Code on your machine:

1. **Download Visual Studio Code**:
   
   Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).

2. **Install Visual Studio Code**:

   - **For Windows**:
     - Download the `.exe` installer for Windows.
     - Run the installer and follow the on-screen instructions. You can choose the default options, but make sure to check the box for **Add to PATH** during the installation process.

   - **For macOS**:
     - Download the `.zip` file for macOS.
     - Extract the zip and drag the **Visual Studio Code** application to your `Applications` folder.

   - **For Linux**:
   
     - Follow the instructions specific to your Linux distribution:

       - **Debian-based (Ubuntu, etc.)**: Run the following commands in your terminal:
         ```bash
         sudo apt update
         sudo apt install -y code
         ```
       - **Red Hat-based (Fedora, CentOS, etc.)**: Run the following commands in your terminal:
         ```bash
         sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
         sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1" > /etc/yum.repos.d/vscode.repo'
         sudo dnf check-update
         sudo dnf install code
         ```

3. **Verify Installation**:

   After the installation is complete, you can verify that Visual Studio Code was installed correctly by opening your terminal or Command Prompt (on Windows) and typing:

   ```bash
   code --version
   ```

## Get Started

To get started with the portfolio website, you need to clone this repository and install the necessary dependencies. If you're not familiar with Git or Node.js, follow the steps below.

### Install Process

To install the portfolio website on your local machine, follow the steps mentioned in the ["Install the Project"](###install-the-project) section.

### Install the Project

Once Git and Node.js are installed, follow these steps to download and set up the portfolio project:

1. **Clone the repository**:

   Open your terminal or Git Bash (on Windows) and type the following command to clone the repository:

   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. **Navigate into the project directory**:

   Once the repository is downloaded, move into the project directory:

   ```bash
   cd portfolio-website
   ```

   For open Visual Studio Code

   ```bash
   code .
   ```

3. **Install dependencies**:

   The project uses Node.js to manage external libraries. To install them run:

   ```bash
   npm install
   ```

4. **Run Process**:

   To install the portfolio website on your local machine, follow the steps mentioned in the "install the Project" section

   ```bash
   npm run dev
   ```

This will launch the website on your local machine for you to view and make adjustments.

## How You Can Customize the Site

Customizing the site to fit your needs is simple. Follow the guidelines below to modify the content and structure of various sections of the website.

### File Path to Customize

The content for the site is stored in the `app/ContentData` directory. To customize any section, follow these steps:

1. **Navigate to the File Path**:
   
   Open the `app/ContentData` directory in your project folder.

2. **Open the Desired File**:
   
   Inside the `ContentData` folder, you'll find various files corresponding to different sections of the website (e.g., "About", "Portfolio", "Contact"). Select the file that corresponds to the section you want to edit.

   For example:
   - If you want to edit the **About** section, open `AboutMeContent.ts`.
   - To modify the **MyWorks** section, open `MyWorksContent.ts` .

3. **Read the Instructions Carefully**:
   
   Inside each file, you'll find structured comments and guidelines for customizing the content. Please read these instructions carefully to ensure that you edit the correct fields and follow the format provided. This will help maintain consistency across the website.

4. **Edit or Add Your Content**:
   
   After reviewing the instructions, you can begin editing the content. Modify the text, images, links, or other elements based on your requirements.

## License

- This project is licensed under the MIT License. This means anyone can clone, fork, and edit this repository for their own use. Contributions are welcome!

## MIT License

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

***Powered by Octopus X***
# Portfolio Website for Thumbnail Designers

## Project Description 

This is an open-source portfolio platform designed specifically for thumbnail designers to showcase their creative work, connect with clients, and build their professional identity. This project provides a modern, customizable, and responsive website template that allows designers to highlight their best projects, share their design process, and establish meaningful connections with potential collaborators or clients.

## Table of Contents

- [Project Description](#project-description)
- [Install the Project](#install-the-project)
  - [Install Git](#install-git)
  - [Install Node.js](#install-nodejs)
  - [Install Visual Studio Code](#install-visual-studio-code)
- [Get Started](#get-started)
  - [Install Process](#install-process)
  - [Run Process](#run-process)
- [How You Can Customize the Site](#how-you-can-customize-the-site)

## Install the Project

To get started with the portfolio website, you need to clone this repository and install the necessary dependencies. If you're not familiar with Git or Node.js, follow the steps below.

### Install Git

Git is a tool for downloading the project from GitHub. If you don’t have Git installed, here’s how you can get it:

1. **Download Git**: Go to the [Git download page](https://git-scm.com/downloads).
2. **Install Git**: Follow the instructions for your operating system (Windows, macOS, or Linux).
   - On Windows, run the installer and select the default settings.
   - On macOS, you may need to install Homebrew first and use `brew install git`.

    After installation, verify that Git is installed by opening a terminal (or Git Bash on Windows) and typing:
     
    ```bash
    git --version
    ```

If you see a version number, Git is installed correctly.

### Install Node.js

Node.js is required to run the website locally. It also helps to manage project dependencies.

1. **Download Node.js**: Go to the [Node.js download page](https://nodejs.org/en/).

2. **Install Node.js**: Download the latest LTS version and follow the installation instructions for your operating system.

   After installation, verify that Node.js is installed by opening a terminal (or Command Prompt on Windows) and typing:

    ```bash
    node --version
    ```

    You should see a version number. Next, check if npm (Node's package manager) is installed by typing:

    ```bash
    npm --version
    ```

If both commands return version numbers, Node.js is set up correctly.

### Install Visual Studio Code

Visual Studio Code (VS Code) is a popular code editor that is highly recommended for editing and managing your project files. Follow these steps to install VS Code on your machine:

1. **Download Visual Studio Code**:
   
   Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).

2. **Install Visual Studio Code**:

   - **For Windows**:
     - Download the `.exe` installer for Windows.
     - Run the installer and follow the on-screen instructions. You can choose the default options, but make sure to check the box for **Add to PATH** during the installation process.

   - **For macOS**:
     - Download the `.zip` file for macOS.
     - Extract the zip and drag the **Visual Studio Code** application to your `Applications` folder.

   - **For Linux**:
   
     - Follow the instructions specific to your Linux distribution:

       - **Debian-based (Ubuntu, etc.)**: Run the following commands in your terminal:
         ```bash
         sudo apt update
         sudo apt install -y code
         ```
       - **Red Hat-based (Fedora, CentOS, etc.)**: Run the following commands in your terminal:
         ```bash
         sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc
         sudo sh -c 'echo -e "[code]\nname=Visual Studio Code\nbaseurl=https://packages.microsoft.com/yumrepos/vscode\nenabled=1\ngpgcheck=1" > /etc/yum.repos.d/vscode.repo'
         sudo dnf check-update
         sudo dnf install code
         ```

3. **Verify Installation**:

   After the installation is complete, you can verify that Visual Studio Code was installed correctly by opening your terminal or Command Prompt (on Windows) and typing:

   ```bash
   code --version
   ```

## Get Started

To get started with the portfolio website, you need to clone this repository and install the necessary dependencies. If you're not familiar with Git or Node.js, follow the steps below.

### Install Process

To install the portfolio website on your local machine, follow the steps mentioned in the ["Install the Project"](###install-the-project) section.

### Install the Project

Once Git and Node.js are installed, follow these steps to download and set up the portfolio project:

1. **Clone the repository**:

   Open your terminal or Git Bash (on Windows) and type the following command to clone the repository:

   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```

2. **Navigate into the project directory**:

   Once the repository is downloaded, move into the project directory:

   ```bash
   cd portfolio-website
   ```

   For open Visual Studio Code

   ```bash
   code .
   ```

3. **Install dependencies**:

   The project uses Node.js to manage external libraries. To install them run:

   ```bash
   npm install
   ```

4. **Run Process**:

   To install the portfolio website on your local machine, follow the steps mentioned in the "install the Project" section

   ```bash
   npm run dev
   ```

This will launch the website on your local machine for you to view and make adjustments.

## How You Can Customize the Site

Customizing the site to fit your needs is simple. Follow the guidelines below to modify the content and structure of various sections of the website.

### File Path to Customize

The content for the site is stored in the `app/ContentData` directory. To customize any section, follow these steps:

1. **Navigate to the File Path**:
   
   Open the `app/ContentData` directory in your project folder.

2. **Open the Desired File**:
   
   Inside the `ContentData` folder, you'll find various files corresponding to different sections of the website (e.g., "About", "Portfolio", "Contact"). Select the file that corresponds to the section you want to edit.

   For example:
   - If you want to edit the **About** section, open `AboutMeContent.ts`.
   - To modify the **MyWorks** section, open `MyWorksContent.ts` .

3. **Read the Instructions Carefully**:
   
   Inside each file, you'll find structured comments and guidelines for customizing the content. Please read these instructions carefully to ensure that you edit the correct fields and follow the format provided. This will help maintain consistency across the website.

4. **Edit or Add Your Content**:
   
   After reviewing the instructions, you can begin editing the content. Modify the text, images, links, or other elements based on your requirements.

## License

- This project is licensed under the MIT License. This means anyone can clone, fork, and edit this repository for their own use. Contributions are welcome!

## MIT License

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

***Powered by Octopus X***
