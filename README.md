# orper-summer-school
 
Move Thymio based on environment
- This repository contains the code related to the creation of an educational activity using the Thymio robot.
- The final goal is that the pupil learns to control the robot by positioning items in the robot environment in a certain way. 
- This is to allow even young children (from ages 3-4 up to learn to program the robot).

Status of code and project
- The code and project have just been started. It is very much still work in progress.
- The current code allows the robot to illuminate its top LEDS based on the tilting of the robot. For instance, if you tilt the robot to the right, the right LED gets illuminated.

Future plans
- The code currently is missing testing. I plan to add several unit tests to this purpose.
- To facilitate dependency management, I plan to use Anaconda.

A - Code
The code is found in the file "Move Thymio based on side tilt.ipynb"

B - Physical setup to run the code
- A computer running MacOS X 10.13 or later, or Windows 7 or later.
- You need to have a Thymio II robot to be able to run the given code. Nonetheless, all installation steps in section C can be followed without the robot. It is also possible to view the code in Jupyter Notebooks by following steps 6 and 7 in the section D below.

C - Install following tools before running the code
1. Install pip, tool for installing python packages: https://pypi.org/project/pip/

2. Install python3: https://www.python.org/downloads/

3. Install Jupyter-notebooks
Using your command line interface, run command: pip install notebook
Further information available here: https://jupyter.org/install

4. Install tdm-client
Using your command line interface, run command: python3 -m pip install tdmclient
Further information available here: https://pypi.org/project/tdmclient/

5. Install ThymioSuite
Download available here: https://www.thymio.org/download-thymio-suite/

D - Steps to run the code
1. Turn on your Thymio robot

2. Connect the Thymio dongle (usb key) to your computer

3. Launch ThymioSuite application

4. Click on "VPL 3"

5. You should see the logo with your Thymio robot appear (do not click on it)

6. Open your command line interface and run command: jupyter-notebook
This should open Jupyter Notebooks in your browser.

7. In Jupyter Notebooks, navigate to the code file "Move Thymio based on side tilt.ipynb" and open it.

8. Select the first cell (block of code) and run it using the keys SHIFT+ENTER.
This cell just needs to be run the first time to connect your notebook to your Thymio.

9. Select the second cell and run it.
This is the actual code.

E - Dependencies
pip 23.2.1
Python 3.11.5
Jupyter-notebook 3.9.6
tdmclient 0.1.20
ThymioSuite 2.4.0