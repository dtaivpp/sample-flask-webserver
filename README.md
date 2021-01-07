# Sample-Webserver

This is a sample webserver project to demonstrate how to build and deploy a webserver to a production environment. 

### Setup 

Clone the repository onto your computer. Then create a virtual environment with the following command. 

This command would read "Use the python module (-m) venv to create a virtual environment named venv". Small note as well depending on how your python was installed you may need to substitute python with python3. 

`python -m venv venv`


Once that has finished which may take a minute you will need to activate the environment. This can be done with the following command. This just sets your shell/terminal to use the python stored in the venv directory.

Mac/Linux: `source venv\bin\activate`

Windows: `venv\Scripts\activate`


Finally install the dependancies:

This command reads "Use the python module (-m) pip to install recursively (-r) our requirements from requirements.txt"
`python -m pip install -r requirements.txt`

