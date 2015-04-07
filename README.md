# aircrack-bws
Copy of aircrack-ng with a few minor modifications to airodump-ng.

Do not use this copy for anything! Only keeping this repo alive for the 1 project that requires it. See https://github.com/Jtfinlay/Burgess for details.

Basically just hardcoded the default refresh rate of printing to console to be 0.5 seconds and removed the limiter on the number
of lines printed so that it was possible to pipe the output from one process to another without data getting dropped.
