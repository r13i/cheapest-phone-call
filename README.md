# cheapest-phone-call
Small challenge to find the best phone operator to use based on call price

### Methodology

- We'll be using Python as programing language as it is pretty straitforward to build a fast prototype of the solution, and also as it offers many libraries aimed at making large datasets manipulation easier (`pandas`, `numpy`, ...)

- We'll be using a Jupyter notebook in order to have a maximum of ergonomy and a beatiful visual presentation. Also, there will be no need to download / re-run the code as it is already displayed in the notebook.

- In case we want to have a production-ready prototype that deals with larger datasets, one of the best choices I propose is to use `Apache Spark` with the `Scala API`, as it is especially aimed for Big Data, and because it runs on the JVM.

### How To

- `$ git clone https://github.com/redouane-dev/cheapest-phone-call.git`
- `$ cd cheapest-phone-call`
- Create a virtual environment to avoid dealing with dependency issues and conflicts : `$ virtualenv -p python3 venv`
- `$ source ./venv/bin/activate`. You'll start seeing a `(venv)` before the shell prompt.
- `(venv) $ pip3 install -r requirements.txt` in order to install all the requirements.

Now you should be all set to run the notebook

- `(venv) $ jupyter notebook prototyping.ipynb
