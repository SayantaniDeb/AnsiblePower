# AnsiblePower

**AnsiblePower** is a lightweight web interface inspired by Ansible Tower. It allows users to manage Ansible playbooks, view and edit host configurations, and monitor system performance via a modern and intuitive web interface.

## Features

### 1. Homepage
- Lists available Ansible playbooks on "PLAYBOOKS_DIR" path 
- Buttons to:
  - **Run**: Executes a playbook and shows the output
  - **Show**: Displays the content of a playbook

### 2. History
- Displays a table of previously run playbooks with timestamps and actions

### 3. Settings
#### Hosts Management
- View and edit `/etc/ansible/hosts` file
- Displays error messages if the user lacks read/write permissions

#### Master Node Status
- Displays CPU and memory usage

#### Clear History
- Deletes all playbook execution history

#### Dark Mode Toggle
- Switch between light and dark modes

### 4. User-Friendly Interface
- Modern design with rounded buttons, smooth animations, and a responsive layout
- Sidebar with toggle functionality for better navigation

## Requirements
- **Python 3.x**
- **Flask** (`pip install flask`)
- **psutil** (`pip install psutil`)
- **Ansible** installed and accessible via `ansible-playbook`
- **Replace below variables with yours in AnsiblePower.py**
  
![image](https://github.com/user-attachments/assets/fb1eb86c-8a41-486b-9e70-2c421b25ca17)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AnsiblePower.git
cd AnsiblePower
```
2. Install dependencies:
```bash
pip install flask psutil
```
3. Run the application:
```bash
python app.py
```
## Contributing :
I welcome contributors to join and improve this project. If you are passionate about DevOps, Flask, or Ansible, your collaboration would be highly appreciated. Feel free to fork the repository, make changes, and submit a pull request.

Contact: I’d love to hear your ideas or suggestions for this project. Let’s collaborate and build something amazing together! You can also reach out to me on GitHub or other platforms.

If you’d like me to update this further with specific URLs or additional details, let me know!
