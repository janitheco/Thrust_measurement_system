# Thrust_measurement_system
This Python script converts thrust measurement data from a serial interface into CSV files. It has been specifically used with an Adam Nymbus analytical balance connected via USB serial interface and runs on a Raspberry Pi 4B. The balance serves as a thrust force measurement system with an inverted experimental thruster mounted on it.

Features

Reads thrust data from the Adam Nymbus analytical balance via USB serial interface.
Stores the data on a Raspberry Pi 4B.
Controls a relay connected to the GPIO pins to start the thruster, which can be customized as needed.
Accepts user inputs for offset, burn time, number of repetitions, and file name.
Automatically saves the output as a CSV file.
Usage

Setup: Ensure the Adam Nymbus analytical balance is connected to the Raspberry Pi via USB and the experimental thruster is mounted on the balance.

Inputs:

Offset: Set the initial offset value for the measurements.
Burn Time: Specify the duration for which the thruster will run.
Number of Repetitions: Indicate how many times the experiment should be repeated.
File Name: Provide a name for the output CSV file.
Execution: Run the script to start the data acquisition and control the thruster.

Customization

Feel free to modify the code to suit your specific needs. Contributions and improvements are welcome!

License

This project is open-source and available under Creative Commons Zero v1.0 Universal.

Contact

For any questions or support, please contact u1129004@anu.edu.au
