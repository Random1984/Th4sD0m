# Th4sD0m
Tool to identify all domains contained in an IP anonymously

# How to install

Install requirements with:

<pre> pip install -r requirements.txt </pre>

#How to use:

Example of usage: 

<pre>python th4sd0m.py -i DIRECTION_IP -n 4 -e Y</pre>


<pre>usage: th4sd0m.py [-h] -i IP -n NUM [-e EXPORT]</pre>


This script identifies all domains contained in an IP

optional arguments:

<pre>

  -h, --help          show this help message and exit
  
  -i IP, --ip IP       The IP which wants to search
 
  
  -n NUM, --num NUM     Indicate the number of the search which you want to do
  
  -e EXPORT, --export EXPORT
  
                        Export the results to a json file (Y/N)
 </pre>
