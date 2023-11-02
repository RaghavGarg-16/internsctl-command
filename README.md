# internsctl-command

## Here's how the script works:

- It defines a variable VERSION to hold the version number.
- It defines two functions show_manual and show_help to display the manual page and usage/help information, respectively.
- It checks the provided argument. If --help is provided, it calls show_help. If --version is provided, it displays the version. Otherwise, it displays an error message.
- Make sure to save this script with the name internsctl and give it execute permissions (chmod +x internsctl). Then, place it in a directory that is included in your system's PATH.

## You can test the command using the following:

 - ./internsctl --help to see usage and examples.
- ./internsctl --version to display the version.
man ./internsctl to view the manual page.
