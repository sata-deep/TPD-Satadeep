# Temperature Programmed Desorption (TPD) rate calculation
This application calculates the temperature programmed desorption rate. The program is written in C++ and Qt.
Once initial coverage, heating rate, desorption energy, temperature range etc are provided the program solves Polyani-Wigner differential equation using Runge Kutta method and prints the coverage and rate in a three column file "Coverage.dat" (1st column=temperature, 2nd column=coverage, 3rd column=rate). Currently the application works for only Linux,
later it will be updated for MAC and windows.
Download the Application file. Change the permissions (in bash you may issue: chmod +x TPD.run)

(Written by :
Satadeep Bhattacharjee,
IKST, Bangalore,
email: satadeep.bhattacharjee@ikst.res.in
)
