
# Tech Environment Setup on macOS

This guide walks you through setting up a complete development environment on your MacBook. It includes the installation of Git, Visual Studio Code, iTerm2, VirtualBox, and Ubuntu, as well as how to sign up for GitHub and AWS.

---

## 1. Installing Git

Git is a version control system that helps you manage your code history.

### Step 1: Check if Git is already installed
Open Terminal and run:
```bash
git --version
```

### Step 2: Install Homebrew (if not already installed)
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### Step 3: Use Homebrew to install Git
```bash
brew install git
```

### Step 4: Confirm installation
```bash
git --version
```

### Screenshot:
![figure-1](https://github.com/user-attachments/assets/0700778a-c4db-445e-855a-fae097cef381)



---

## 2. Installing Visual Studio Code

VS Code is a lightweight, powerful code editor.

### Step 1: Download the installer
Visit: [https://code.visualstudio.com/](https://code.visualstudio.com/)

### Step 2: Install
- Open the downloaded `.dmg` file.
- Drag Visual Studio Code to the Applications folder.

### Step 3: Add VS Code to PATH (optional)
```bash
export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
```

### Screenshot:
![Untitled](https://github.com/user-attachments/assets/95ebd83a-693f-4ab1-9e6a-7b59bb97072e)


---

## 3. Installing iTerm2

iTerm2 is an improved terminal emulator for macOS.

### Step 1: Download from:
[https://iterm2.com/downloads.html](https://iterm2.com/downloads.html)

### Step 2: Install
- Open the `.zip` file and move iTerm2 to the Applications folder.

### Step 3: Launch and customize preferences if needed.

### Screenshot:
![Untitled18](https://github.com/user-attachments/assets/31c72960-bdca-4e26-9ea3-bfa7906c902c)


---

## 4. Installing VirtualBox

VirtualBox allows you to run virtual machines like Ubuntu on your Mac.

### Step 1: Download VirtualBox
[https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

### Step 2: Install
- Open the downloaded `.dmg` file.
- Run the installer and follow on-screen instructions.

### Step 3: Confirm installation
```bash
VBoxManage --version
```

### Screenshot:

![Untitled23](https://github.com/user-attachments/assets/0e393fa9-88ab-45e5-8403-49f41d7e4649)

---

## 5. Installing Ubuntu on VirtualBox

Ubuntu is a popular Linux distribution.

### Step 1: Download Ubuntu ISO
[https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop)

### Step 2: Create a new VM in VirtualBox
- Open VirtualBox
- Click “New” and enter a name (e.g. Ubuntu)
- Type: Linux
- Version: Ubuntu (64-bit)
- Allocate memory (e.g. 4GB)
- Create a virtual hard disk (e.g. 20GB)

### Step 3: Attach Ubuntu ISO and start installation
- In Settings > Storage, choose the downloaded ISO
- Start the VM and follow Ubuntu installation steps

### Screenshot:
![choose-keyboard-layout-for-ubuntu-20 04](https://github.com/user-attachments/assets/3d230d87-2841-423a-a08c-f90cd1b6f443)


---

## 6. Signing Up on GitHub

GitHub is a code hosting platform for version control and collaboration.

### Step 1: Visit
[https://github.com](https://github.com)

### Step 2: Click on "Sign up" and fill out:
- Username
- Email
- Password

### Step 3: Verify your account via email

### Step 4: Install GitHub CLI (optional)
```bash
brew install gh
```

### Screenshot:
<img width="602" alt="Screenshot 2025-04-19 at 1 51 03 PM" src="https://github.com/user-attachments/assets/44f04956-fcf5-4df5-bbef-3585868d8100" />


---

## 7. Signing Up on AWS

AWS offers cloud computing services and tools.

### Step 1: Visit
[https://aws.amazon.com/](https://aws.amazon.com/)

### Step 2: Click on “Create an AWS Account”

### Step 3: Fill in the required information:
- Email address
- Password
- Account name

### Step 4: Provide billing details and phone number verification

### Step 5: Select a support plan (Free Tier is recommended for beginners)

### Screenshot:
<img width="1109" alt="Screenshot 2025-04-19 at 1 52 26 PM" src="https://github.com/user-attachments/assets/0d497369-cc58-4dd0-b8a1-71bf23bc0335" />


---

