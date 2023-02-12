# Shono Project
Hard work is worthless for those that don't believe in themselves
## Authors
- [@shonoYuji](https://github.com/shonoYuji)
## Sample Code
`printf(" Hello World ");`
## How to Install and set up Git
##### Step 1: Install Git
- For Windows: [Download the Git installer](https://git-scm.com/download/win). To open a command window, go to Git Bash.vbs from the Git folder of the Programs directory.
- For Mac: [Download the Git installer](https://git-scm.com/download/win). To open a command window, search for the Terminal.
- For Linux: Enter `sudo apt-get install git` at the command line. To verify installation was successful, enter `which git`.
##### Step 2: Update your configuration file
1. Enter the following command to configure your username, replacing Emma's name with your own. (Copy and paste the line after the `$` and press enter.)
`$ git config --global user.name "Emma Paris"`
2. Enter the following command to configure your email address, replacing Emma's email address with your own.
`$ git config --global user.email "eparis@atlassian.com"`
3. Configure Git to handle line endings properly so that Bitbucket doesn't think files have changed when the actual content hasn't changed. We recommend this setting if you're collaborating on repositories with others who have different operating systems.
- For Windows - `$ git config --global core.autocrlf true`
- For Mac and Linux - `$ git config --global core.autocrlf input`
