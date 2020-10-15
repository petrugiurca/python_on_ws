<style>
mark { 
background-color: silver;
color: black;
}
</style>
<h1>Python on Windows</h1>	

<h3>#Python 2</h3>
<ol>
<li>Install <a href="https://www.python.org/downloads/release/python-277/">Python 2.7</a></li>
<ul>

<li>To use <mark>pygame</mark> (mentioned below), install the 32-bit (x86, not x86-64) version of Python!</li>
<li>Location <mark>C:\Python27</mark></li>
<li>Add <mark>C:\Python27\python.exe</mark> and <mark>C:\Python27\Scripts</mark> to <mark>PATH</mark></li>
<li>In the Start menu, rename the "IDLE" shortcut to "IDLE Python 2.7"</li>

</ul>

<li>Install <mark>pip</mark> for package management (<a href="https://pip.pypa.io/en/latest/installing/">https://pip.pypa.io/en/latest/installing/</a>)</li>
<ul>

<li>Download <mark>get-pip.py</mark> and run <mark>python get-pip.py</mark>, where <mark>python</mark> is the command to run the Python 2.7 interpreter.</li>
<li>If this works, <mark>C:\Python27\Scripts</mark> will contain <mark>pip.exe</mark></li>
	
</ul>


<li>Install <mark>virtualenv</mark> for environment management (<a href="https://docs.python.org/3/library/venv.html">https://docs.python.org/3/library/venv.html</a>)</li>
<ul>

<li><mark>pip install virtualenv</mark> where <mark>pip</mark> refers to <mark>C:\Python27\Scripts\pip.exe</mark></li>
	
</ul>

<li>Install virtualenvwrapper for Powershell: makes virtualenv usage more convenient <a href="https://pypi.python.org/pypi/virtualenvwrapper-powershell/2.7.1"></a> (https://pypi.python.org/pypi/virtualenvwrapper-powershell/2.7.1)</li>
<ul>

<li><mark>pip install virtualenvwrapper-powershell</mark></li>
<li>Add <mark>Import-Module virtualenvwrapper</mark> to PowerShell profile for all users</li>
<li>See sample PowerShell profile below</li>

</ul>


<li>Install other useful packages for education:</li>
<ul>

<li><mark>pip install ipython</mark></li>
<li>Install pygame (download msi file from <a href="http://pygame.org/download.shtml">http://pygame.org/download.shtml</a>)</li>
	
</ul>

</ol>


<h3>#Python 3</h3>
	
<ol>
<li>Install <a href="https://www.python.org/downloads/release/python-390/">Python 3.9</a></li>
<ul>

<li>To use <mark>pygame</mark> (mentioned below), install the 32-bit (x86, not x86-64) version of Python!</li>
<li>Location <mark>C:\Python39</mark></li>
<li>Add <mark>C:\Python39\python.exe</mark> and <mark>C:\Python39\Scripts</mark> to <mark>PATH</mark></li>
<li>In the Start menu, rename the "IDLE" shortcut to "IDLE Python 3.9"</li>

</ul>


<li>Install pip for package management (<a href="https://pip.pypa.io/en/latest/installing/">https://pip.pypa.io/en/latest/installing/</a>)</li>
<ul>

<li>Download <mark>get-pip.py</mark> and run <mark>python get-pip.py</mark>, where <mark>python</mark> is the command to run the Python 3.9 interpreter.</li>
<li>If this works, <mark>C:\Python39\Scripts</mark> will contain <mark>pip.exe</mark></li>

</ul>


<li>Install other useful packages for education:</li>
<ul>

<li><mark>pip install ipython</mark></li>
<li>Install pygame (download msi file from <a href="http://pygame.org/download.shtml">http://pygame.org/download.shtml</a>)</li>

</ul>
</ol>	


