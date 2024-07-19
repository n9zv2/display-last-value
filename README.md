# Control Panel Project

## Overview

This project involves a web-based control panel with buttons for different commands. When a button is pressed, the command is printed on another page and saved in a MySQL database. The following images illustrate the key components of the project.

## Images

### 1. Control Panel Interface

![control-panal-page](https://github.com/user-attachments/assets/b96d5c9b-8f61-4d20-b92f-57252fdd5316)

The first image shows the main interface of the control panel. It consists of four buttons:
- **Forward** (Green)
- **Backward** (Red)
- **Left** (Blue)
- **Right** (Yellow)

Each button sends a corresponding command when pressed.

### 2. Command Confirmation Page

![last-button-page](https://github.com/user-attachments/assets/1afdfe2e-d7ba-4f98-9b37-dc8553ed61da)

The second image displays the command confirmation page. After a button is pressed on the control panel, this page shows the last command executed. In this example, the "Left" command was the last button pressed.

### 3. MySQL Database Record


![last-button sql](https://github.com/user-attachments/assets/8ac82218-97b1-40ac-aae8-8c51a8ad9a83)


The third image illustrates the MySQL database records of the commands. Each entry includes:
- **Timestamp**: The exact time when the command was executed.
- **Direction**: The command given (e.g., forward, backward, left, right).
- **ID**: A unique identifier for each command.

## Functionality

- **Control Panel Interface**: Users interact with this panel to send commands.
- **Command Confirmation**: Confirms the last command executed and provides immediate feedback to the user.
- **Database Storage**: Records all commands along with their execution times for future reference.
