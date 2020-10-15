###### <h1>Python on Windows</h1>

#Python 2

Install Python 2.7.7 (https://www.python.org/downloads/release/python-277/)
To use pygame (mentioned below), install the 32-bit (x86, not x86-64) version of Python!
Location C:\Python27
Add C:\Python27\python.exe and C:\Python27\Scripts to PATH
In the Start menu, rename the "IDLE" shortcut to "IDLE Python 2.7"
Install pip for package management (https://pip.pypa.io/en/latest/installing/)
Download get-pip.py and run python get-pip.py, where python is the command to run the Python 2.7 interpreter.
If this works, C:\Python27\Scripts will contain pip.exe
Install virtualenv for environment management (https://docs.python.org/3/library/venv.html)
pip install virtualenv where pip refers to C:\Python27\Scripts\pip.exe
Install virtualenvwrapper for Powershell: makes virtualenv usage more convenient (https://pypi.python.org/pypi/virtualenvwrapper-powershell/2.7.1)
pip install virtualenvwrapper-powershell
Add Import-Module virtualenvwrapper to PowerShell profile for all users
See sample PowerShell profile below
Install other useful packages for education:
pip install ipython
Install pygame (download msi file from http://pygame.org/download.shtml)

#Python 3

Install Python 3.9.0 (https://www.python.org/downloads/release/python-390/)
To use pygame (mentioned below), install the 32-bit (x86, not x86-64) version of Python!
Location C:\Python39
Add C:\Python39\python.exe and C:\Python39\Scripts to PATH
In the Start menu, rename the "IDLE" shortcut to "IDLE Python 3.9"
Install pip for package management (https://pip.pypa.io/en/latest/installing/)
Download get-pip.py and run python get-pip.py, where python is the command to run the Python 3.9 interpreter.
If this works, C:\Python39\Scripts will contain pip.exe
Install other useful packages for education:
pip install ipython
Install pygame (Download msi file from http://pygame.org/download.shtml)
