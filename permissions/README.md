# Permissions

Welcome to the Permissions project! This directory contains exercises and scripts to help you understand file permissions in Unix.

## Table of Contents
- [Description](#description)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Files](#files)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Author](#author)

## Description
This project focuses on file permissions in Unix. It includes various scripts to practice these concepts.

## Requirements
- Unix-based operating system
- A text editor or IDE (e.g., Visual Studio Code, Vim)

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/JaysonPasquier/holbertonschool-shell.git
    ```
2. Navigate to the project directory:
    ```bash
    cd holbertonschool-shell/permissions
    ```

## Usage
To run any of the shell scripts in this directory, use the following command:
```bash
./filename.sh
```

## Files
- `0-iam_betty`: A script that switches the current user to the user betty.
- `1-who_am_i`: A script that prints the effective username of the current user.
- `2-groups`: A script that prints all the groups the current user is part of.
- `3-new_owner`: A script that changes the owner of the file hello to the user betty.
- `4-empty`: A script that creates an empty file called hello.
- `5-execute`: A script that adds execute permission to the owner of the file hello.
- `6-multiple_permissions`: A script that adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- `7-everybody`: A script that adds execution permission to the owner, the group owner, and the other users, to the file hello.
- `8-James_Bond`: A script that sets the permission to the file hello as follows: Owner - no permission, Group - no permission, Other users - all permissions.
- `9-John_Doe`: A script that sets the mode of the file hello to -rwxr-x-wx.
- `10-mirror_permissions`: A script that sets the mode of the file hello the same as olleh’s mode.
- `11-directories_permissions`: A script that adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.
- `12-directory_permissions`: A script that creates a directory called my_dir with permissions 751 in the working directory.
- `13-change_group`: A script that changes the group owner to school for the file hello.
- `14-change_owner_and_group`: A script that changes the owner to betty and the group owner to holberton for all the files and directories in the working directory.
- `15-symbolic_link_permissions`: A script that changes the owner and the group owner of the file _hello to betty and holberton respectively.
- `16-if_only`: A script that changes the owner of the file hello to betty only if it is owned by the user guillaume.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your changes. Ensure that your code follows the project's coding standards and includes appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](../LICENSE) file for more details.

## Acknowledgments
- [Holberton School](https://www.holbertonschool.com/) for providing the project requirements and guidance.
- [Unix Documentation](https://www.gnu.org/software/coreutils/manual/html_node/Directory-Setuid-and-Setgid.html) for the comprehensive reference.

## Author
This project was created by [JaysonPasquier](https://github.com/JaysonPasquier).
For any inquiries, please contact me at jaysonpasquier.contact@gmail.com.
