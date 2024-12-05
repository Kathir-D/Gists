# My Gists


This document provides an overview of my scripts available in my [GitHub Gists](https://gist.github.com/Kathir-D):

## [RepeatAppOpenerPowershell.ps1](https://gist.github.com/Kathir-D/bc519150645a25dcfd1be0bf6754480b#file-repeatappopenerpowershell-ps1)

This PowerShell script is designed for Windows systems to ensure a specified application remains running. It periodically checks if the application is active and relaunches it if necessary. Key features include:

- **Initial Delay**: Waits for a user-defined period before the first launch.
- **Regular Checks**: Monitors the application's status at set intervals.
- **User Interaction**: Allows users to terminate the script by typing 'quit' during waits.

Users can customize the application's path, name, initial wait time, and check intervals within the script.

## [RepeatAppOpener.sh](https://gist.github.com/Kathir-D/2682ea3831b79626bf6ba3c5b1f5a76b#file-RepeatAppOpener.sh)

This Bash script serves a similar purpose for Unix-like systems, such as macOS or Linux. It ensures a specified application remains active by:

- **Initial Delay**: Pausing for a set time before the first application launch.
- **Continuous Monitoring**: Regularly verifying if the application is running and restarting it if it's not.
- **User Control**: Providing the option to stop the script by typing 'quit' during wait periods.

Customization options include setting the application's path, name, initial wait time, and check intervals.

Both scripts are useful for maintaining the continuous operation of critical applications on their respective platforms.
