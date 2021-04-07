# Install Python, virtualenv and Jupyter

## If you never heard of Python and/or havent installed it yet

* Head to <https://docs.anaconda.com/anaconda/install/windows/> and install Anaconda
* Open the Anaconda Navigator and start Jupyter: <https://docs.anaconda.com/anaconda/user-guide/getting-started/> (scroll down to "Run Python in a Jupyter Notebook")
* In Jupyter click on Upload and upload the notebook provided
* If some packages are missing, use the Navigator to create an environment and install the missing packages: <https://docs.anaconda.com/anaconda/navigator/getting-started/>


## If you are already using Python

* Create a new environment with virtualenv:
	- virtualenv -p python3 myvenv && source myenv/bin/activate && pip install jupyter rdflib requests pandas SPARQLWrapper ipyleaflet
	- with pipenv: pipenv shell && pipenv install jupyter rdflib requests pandas SPARQLWrapper ipyleaflet
* Start the Jupyter notebook:
	- Jupyter notebook
* And open the notebook provided


If you need help drop me an email: [matthias.schloegl@oeaw.ac.at](mailto:matthias.schloegl@oeaw.ac.at)
