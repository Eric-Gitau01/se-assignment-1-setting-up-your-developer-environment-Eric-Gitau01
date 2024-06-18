[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15266491&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11



   ![alt text](<img/Screenshot (232).png>)

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   ![alt text](<img/Screenshot (233).png>)
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   [text](README.md) ![text](<img/Screenshot (234).png>) ![text](<img/Screenshot (235).png>)

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
   
![alt text](<img/Screenshot (237).png>)

5. Install Package Managers:
   If applicable, install package managers like pip (Python).


## Installing Package Managers

### 1. Install pip for Python
pip is the package installer for Python, allowing you to install and manage additional libraries and dependencies.

#### Steps to Install pip:

1. **Update the package list:**
   ```bash
   sudo apt update
   ```

2. **Install pip for Python 3:**
   ```bash
   sudo apt install python3-pip -y
   ```

3. **Verify the installation:**
   ```bash
   pip3 --version
   ```

### 2. Install npm for Node.js
npm is the package manager for Node.js, providing access to a vast repository of JavaScript libraries.

#### Steps to Install npm:

1. **Update the package list:**
   ```bash
   sudo apt update
   ```

2. **Install Node.js and npm:**
   (If not already installed)
   ```bash
   sudo apt install nodejs npm -y
   ```

3. **Verify the installation:**
   ```bash
   npm --version
   ```

### 3. Install Yarn (Alternative JavaScript Package Manager)
Yarn is an alternative package manager for Node.js projects, known for its speed and reliability.

#### Steps to Install Yarn:

1. **Configure the Yarn repository:**
   ```bash
   curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
   echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
   ```

2. **Update the package list:**
   ```bash
   sudo apt update
   ```

3. **Install Yarn:**
   ```bash
   sudo apt install yarn -y
   ```

4. **Verify the installation:**
   ```bash
   yarn --version
   ```

### 4. Install RubyGems for Ruby
RubyGems is the package manager for Ruby, allowing you to install and manage Ruby libraries.

#### Steps to Install RubyGems:

1. **Update the package list:**
   ```bash
   sudo apt update
   ```

2. **Install Ruby:**
   ```bash
   sudo apt install ruby-full -y
   ```

3. **Verify the installation:**
   ```bash
   ruby --version
   ```

4. **Verify RubyGems is installed (should come with Ruby):**
   ```bash
   gem --version
   ```

### 5. Install Composer for PHP
Composer is the dependency manager for PHP, allowing you to manage project dependencies.

#### Steps to Install Composer:

1. **Update the package list:**
   ```bash
   sudo apt update
   ```

2. **Install PHP:**
   ```bash
   sudo apt install php php-cli -y
   ```

3. **Download the Composer installer:**
   ```bash
   php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
   ```

4. **Verify the installer SHA-384 (optional but recommended for security):**
   ```bash
   php -r "if (hash_file('sha384', 'composer-setup.php') === 'YOUR_HASH_HERE') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
   ```

5. **Install Composer:**
   ```bash
   sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer
   ```

6. **Verify the installation:**
   ```bash
   composer --version
   ```

### 6. Install Homebrew (Linuxbrew)
Homebrew is a package manager for macOS and Linux, providing an easy way to install many Unix tools and applications.

#### Steps to Install Homebrew:

1. **Install dependencies:**
   ```bash
   sudo apt update
   sudo apt install build-essential curl file git -y
   ```

2. **Install Homebrew:**
   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

3. **Add Homebrew to your PATH:**
   ```bash
   echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.profile
   eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
   ```

4. **Verify the installation:**
   ```bash
   brew --version
   ```

## Conclusion
With these package managers installed, you will be well-equipped to manage dependencies for a wide range of programming languages and development environments. Each tool offers robust solutions for handling libraries and packages, ensuring that your development process is efficient and up-to-date.


6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   ![alt text](<img/Screenshot (238).png>)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   ### Visual Studio Code (VSCode)

1. **Python**
   - **[Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)**: Provides syntax highlighting, linting, debugging support, and more for Python development.
   - **[Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)**: Offers advanced type checking, autocomplete, and type information for Python.

2. **JavaScript/TypeScript**
   - **[ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)**: Integrates ESLint for JavaScript and TypeScript code linting.
   - **[Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)**: Allows debugging JavaScript code running in the Chrome browser.

3. **Version Control**
   - **[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)**: Enhances Git integration with inline blame annotations, code lens, and more.
   - **[GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)**: Manage GitHub pull requests directly within VSCode.

4. **Other Useful Extensions**
   - **[Docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)**: Simplifies Dockerfile and Docker-compose.yml editing.
   - **[Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)**: Collaborative editing and debugging in real-time.

### IntelliJ IDEA (Java/Scala/Kotlin)

1. **Java**
   - **[CheckStyle](https://plugins.jetbrains.com/plugin/1065-checkstyle-idea)**: Integrates CheckStyle for code style checking in Java.
   - **[JUnit](https://plugins.jetbrains.com/plugin/1467-junit)**: Support for JUnit testing framework.

2. **Version Control**
   - **Built-in Git and GitHub integration**: IntelliJ IDEA comes with built-in support for Git and GitHub, including pull requests and code reviews.

3. **Other Languages**
   - **[Scala](https://plugins.jetbrains.com/plugin/1347-scala)**: Adds Scala support to IntelliJ IDEA.
   - **[Kotlin](https://plugins.jetbrains.com/plugin/6954-kotlin)**: Adds Kotlin support to IntelliJ IDEA.

### Sublime Text

1. **General**
   - **[Package Control](https://packagecontrol.io/)**: Package manager for Sublime Text, allows easy installation of plugins.

2. **Python**
   - **[Anaconda](http://damnwidget.github.io/anaconda/)**: Provides Python and Django support, including linting, autocomplete, and more.

3. **JavaScript**
   - **[SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)**: Framework for linting in Sublime Text, supports many languages including JavaScript.

### Atom

1. **General**
   - **[Atom IDE](https://ide.atom.io/)**: Adds IDE-like features to Atom, including code navigation, diagnostics, and more.

2. **Python**
   - **[python-language-server](https://atom.io/packages/python-language-server)**: Provides Python support using the language server protocol.

3. **JavaScript**
   - **[linter-eslint](https://atom.io/packages/linter-eslint)**: ESLint integration for Atom, helps with JavaScript linting.

### Note on Extension Installation
- To install extensions, plugins, or add-ons, typically you can search for them within your editor or IDE's extension marketplace. Most provide a straightforward installation process directly from the editor itself or through a package manager.

By leveraging these extensions, you can tailor your development environment to suit specific needs, whether it's enhancing language support, improving code quality through linting, or integrating seamlessly with version control systems like Git. Always explore new extensions that fit your workflow to optimize productivity and code quality.


9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

    # Developer Environment Setup Documentation

## Table of Contents

1. **System Specifications**
2. **Installation of Development Tools**
3. **Configuration and Customization**
4. **Troubleshooting Steps**
5. **Additional Resources**

---

## 1. System Specifications

- **Operating System**: Ubuntu 22.04 LTS
- **Processor**: Intel Core i7-9700K
- **Memory**: 32 GB DDR4 RAM
- **Storage**: 1 TB NVMe SSD

## 2. Installation of Development Tools

### 2.1 Update System Packages
First, ensure that all system packages are up to date.
```bash
sudo apt update && sudo apt upgrade -y
```

### 2.2 Install Git
Git is essential for version control.
```bash
sudo apt install git -y
```

### 2.3 Install Node.js and npm
Node.js and npm are required for many JavaScript-based projects.
```bash
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs
```

### 2.4 Install Python and pip
Python is needed for scripting and various development tools.
```bash
sudo apt install python3 python3-pip -y
```

### 2.5 Install Docker
Docker is used for containerization.
```bash
sudo apt install apt-transport-https ca-certificates curl software-properties-common -y
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
sudo apt update
sudo apt install docker-ce -y
```

### 2.6 Install VSCode
VSCode is the preferred code editor.
```bash
sudo snap install --classic code
```

### 2.7 Install Java (Optional)
Java might be needed for certain projects.
```bash
sudo apt install openjdk-11-jdk -y
```

## 3. Configuration and Customization

### 3.1 Configure Git
Set up your Git configuration with your user information.
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 3.2 VSCode Extensions
Install useful extensions for development:
- **Python**: Microsoft Python extension
- **ESLint**: Integrates ESLint into VSCode
- **Docker**: Tools for Docker integration
- **Prettier**: Code formatter

You can install these extensions directly from the VSCode Extensions marketplace.

### 3.3 Configure Docker
Add your user to the Docker group to avoid needing `sudo` for Docker commands.
```bash
sudo usermod -aG docker ${USER}
```
Log out and log back in to apply the group change.

### 3.4 Python Virtual Environments
Set up a virtual environment for Python projects.
```bash
python3 -m venv myenv
source myenv/bin/activate
```



### 3.5 Custom Aliases
Add custom aliases to your `.bashrc` or `.zshrc` file for convenience.
```bash
echo "alias gs='git status'" >> ~/.bashrc
echo "alias ga='git add'" >> ~/.bashrc
echo "alias gc='git commit'" >> ~/.bashrc
source ~/.bashrc
```

## 4. Troubleshooting Steps

### 4.1 Docker Permissions Issue
If you encounter permissions issues with Docker, ensure your user is part of the Docker group and restart your session.

```bash
sudo usermod -aG docker ${USER}
newgrp docker
```

### 4.2 Node.js Version Conflicts
If you encounter issues with Node.js versions, consider using `nvm` (Node Version Manager).
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
source ~/.nvm/nvm.sh
nvm install node
```

### 4.3 Python Package Conflicts
Use virtual environments to avoid conflicts between Python packages.
```bash
python3 -m venv myenv
source myenv/bin/activate
pip install <package_name>
```

## 5. Additional Resources

- [Ubuntu Documentation](https://help.ubuntu.com/)
- [Git Documentation](https://git-scm.com/doc)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Python Documentation](https://docs.python.org/3/)
- [Docker Documentation](https://docs.docker.com/)
- [VSCode Documentation](https://code.visualstudio.com/docs)

---

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
