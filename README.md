How to get into FTP on DJI Mavic Pro
===================

Install Python 2.7 for macOS ([Get installer from python.org](https://www.python.org/downloads/mac-osx/))

Enter the following commands in order:

 2. `git clone https://github.com/douglance/pyduml.git`
 1. `cd pyduml`  
 3. `virtualenv -p python2.7 env`
 4. `source env/bin/activate`
 5. `pip install pathlib`
 6. `pip install pyserial`
 7. `python pyduml.py`
 8. `1` to select Aircraft
 9. `ftp 192.168.42.2`
 10. You're in!
