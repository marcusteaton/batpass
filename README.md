This code snippet can be added to a batch script to prompt for a password before continuing.

Setup:

Replace all astrisks with the number of characters that the password will be.
Replace all ampersands with the desired password, unencrypted.

Known issues:

User can view the batch script and view the password.
User can escape password field and cause script to crash by typing various characters that are interpreted by cmd.exe.