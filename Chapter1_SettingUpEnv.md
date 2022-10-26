<h2>Checklist</h2>

<li>Make sure Kali VM is up to date
<li>Make sure Python3 is up to date
<li>Install venv 
<li>Install your IDE

***
Once Virtual Env. is installed note: 

The following command activates your venv (virtual environment) 
````
usename@kali:~/bhp: source venv/3/bin/activate
````
To exit simply type
````
 (venv3) usename@kali:~/bhp: deactivate
 ````
***
* "you no longer have to specify python3—just python is fine, since that is what we installed into the virtual environment."
***

**Pip: to install Python packages into the virtual environment**
**EXAMPLE** Install lmxl module 
 ````
 (venv3) usename@kali:~/bhp: pip install lxml
 ````
*** 

<h2>Installing your IDE</h2> 

* I like VS code so im going to do the following 
- visit : https://code.visualstudio.com/download/ 
- and install the latest 
- next run the install command **make sure you are in the dir containing the amd_64.deb file**
````
username@kali: sudo apt-get install - f /code1.72.2-...amd64.deb
````

****
BHP Organizes code in the following format/hierarchy 
1. From Imports 
2. Imports 
3. Functions 
4. Class Definitions 
5. Main Block 
****








