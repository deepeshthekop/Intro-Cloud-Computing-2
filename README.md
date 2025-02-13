Cloud Computing: Service Composition

* Use the Docker Desktop to pull the SciPY: docker pull jupyter/scipy-notebook.
* Create two instances of the container by running:
docker run -it -p 8888:8888 jupyter/scipy-notebook
and
docker run -it -p 8889:8888 jupyter/scipy-notebook.
* Access the Jupyter service in your browser using the URL:
http://127.0.0.1:8889/lab?token=Token_Value
where token_value would be provided by the server in the execution flow.
* Start a Jupyter notebook.
* Upload the dataset to the notebook (the abc.csv file).
* Paste the contents of linReg.py file in a single cell or run each statement in a
single cell.