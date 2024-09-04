# Dashboard-app Backend

Make sure python is installed on your machine.  
Python can be installed at: https://www.python.org/downloads/

## For running the backend(Without Docker):

1. Open up terminal at the project directory.
2. Change the directory to backend using "cd backend" command.
3. Run the command "python3 startserver.py".
   By running this, the python script will:

- Install the required dependencies for the backend.
- Run the Unit and Integration tests.
- Start the server at local host 8000.
  The data can be seen at the the following URLs.
- http://localhost:8000/api/candlestick-data/
- http://localhost:8000/api/line-chart-data/
- http://localhost:8000/api/bar-chart-data/
- http://localhost:8000/api/pie-chart-data/

## For running the backend(With Docker):

Download docker at: https://www.docker.com/products/docker-desktop/

1. Make sure the docker deamon is running. Meaning, after installing the Docker desktop app, open it and have it running in the background
2. Open up terminal at the project folder.
3. Change the directory to backend using "cd backend" command.
4. Run the command "docker build -t backend ."
5. Verify the build using the command "docker images"
6. Run the command "docker run -p 8000:8000 backend".

The data can be seen at the the following URLs.

- http://localhost:8000/api/candlestick-data/
- http://localhost:8000/api/line-chart-data/
- http://localhost:8000/api/bar-chart-data/
- http://localhost:8000/api/pie-chart-data/
