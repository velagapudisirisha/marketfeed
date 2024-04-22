# marketfeed
Prerequisites:
---------------
Python: This script requires Python to be installed on your system. It has been tested with Python 3.x.
Dependencies:
--------------
None
Testing:
------------
You can test the script by following the steps above and observing its behavior when monitoring a sample log file. Additionally, you can create different log files with various entries to test different scenarios and see how the script analyzes and reports on the log data.
1. Create a EC2 instance
2.  Install Python 
sudo yum check-update
sudo yum install python3
python --version
3. Create vi log-monitor.py
4. Give permissions chmod +X log-monitor.py
5. Create a sample-log-file.log in sample path. Let say /opt/sample-log-file.log
6. Provide the path in log-monitor.py script
7.  Execute  log-monitor.py
8. Observe the Output
