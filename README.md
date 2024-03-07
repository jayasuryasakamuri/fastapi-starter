## fastapi-starter

* Click on `Use this template` button to create a new repository with the same contents as this repository.
* Clone your newly created repo to your local machine.

### Steps for Mac:

* Go to cloned repo folder
```
cd fastapi-starter/
```
* Create python virtual environment
```
python3 -m venv .venv
```
* Activate the virtual environment
```
source .venv/bin/activate
```
* Install the dependencies for our code
```
pip install -r requirements.txt
```
* Finally run server using below command. This will start the server listening on `http://127.0.0.1:8000`
```
uvicorn main:app --reload
```
Automatic interactive Swagger API documentation is available at `http://127.0.0.1:8000/docs`

