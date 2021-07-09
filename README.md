# Overview

* This script enables testing and visual plotting of the PID control algorithm used in our smoker controller platform.
* Version: 0.1

# Installation
Setup your venv and run install the dependancies from Requirements.txt

# Running
python test_pid.py

# Reading the output
The orange trace is a step input function and the blue trace is your PID loop selected parameters. This script is designed to test the PID loop's response to the transient (rapid change) in conditions. This will help you understand if your control loop is under damped, over damped or critically damped - stable or essentially unstable.

### Who do I talk to? ###
support@trumakers.com