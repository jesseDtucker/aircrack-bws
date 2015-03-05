# aircrack-bws
Copy of aircrack-ng with a few minor modifications to airodump-ng.

Basically just hardcoded the default refresh rate of printing to console to be 0.5 seconds and removed the limiter on the number
of lines printed so that it was possible to pipe the output from one process to another without data getting dropped.
