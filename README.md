# Gym Management System

## Description
A console-based C++ application to manage gym memberships. Users can join, edit their profiles, and quit the gym. Admins can manage member records.

## Features

### User Mode
- **Join Gym:** Register as a gym member.
- **Quit Gym:** Deregister from the gym.
- **Edit Profile:** Update profile information.

### Admin Mode
- **Create Member:** Add new members.
- **Display All Members:** View all member records.
- **Search Member:** Find a member by number.
- **Edit Member:** Update member information.
- **Delete Member:** Remove a member.

## Usage

### Compilation and Execution
1. Compile:
    ```sh
    g++ main.cpp -o gym_management
    ```
2. Run:
    ```sh
    ./gym_management
    ```

### User Mode
1. Select `1` for User Mode.
2. Follow the prompts to join, edit profile, or quit.

### Admin Mode
1. Select `2` for Admin Mode.
2. Use admin code (`adminA1`, `adminA2`, `adminA3`) and password (`gymadmin123`).
3. Manage members with the provided options.

## Files
- `main.cpp`: Source code.
- `newdata2.dat`: Member data file.
- `tips.txt`: Fitness tips file.
