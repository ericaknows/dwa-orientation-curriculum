# Common WSL Debugging

## WSL2 invalid machine configuration troubleshooting

1. If you encounter the error message "WSL2 is not supported with your current machine configuration," it may be necessary to configure your BIOS settings. Follow the instructions provided in this link to enable virtualization in your BIOS: [BIOS Configuration for WSL2](https://bce.berkeley.edu/enabling-virtualization-in-your-pc-bios.html).
2. Open Windows Terminal as an administrator.
3. Run the command "dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart".
4. Restart your computer to complete the installation.
5. Open Windows Terminal as an administrator.
6. Run the command "wsl --set-version Ubuntu 2" and wait for the message "Conversion complete" or "This distribution is already the requested version".
7. If you still receive the error "WSL2 is not supported with your current machine configuration," continue with WSL1 and go back to step 8 of the [Instructions to install Windows Subsystem for Linux](#instructions-to-install-windows-subsystem-for-linux).

---

## How to reset the password for the UNIX user in WSL

1. Open "PowerShell" as an administrator.
2. Run the command `wsl -u root` to run the distribution as a root user.
3. Use the command `passwd userName`, replacing userName with the name of the user you created.
4. You will be asked to set the password. Note that for security reasons, the system will not display your typing, so type carefully.
5. Retype the same password when prompted and press 'enter'.
6. If you see the message `passwd: password updated successfully`, the process is complete.
7. Use the command `logout` to exit the root WSL session.
8. Close the command prompt.

---

## Unregister WSL

This process removes the current WSL setup completely allowing a fresh start in the event something goes incorrectly in the setup process. This will completely reset all  steps in our process so only do this if absolutely required.

1. Open "PowerShell" as an administrator.
2. Run the command `wsl --unregister ubuntu`
3. Restart installation process

---