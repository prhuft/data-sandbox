install these manually using 
pipenv install ./whl/wheel_file.whl

These lines were in the Pipfile but the pipenv install failed:

gdal = {path = "./whl/GDAL-3.4.1-cp39-cp39-win_amd64.whl"}
fiona = {path = "./whl/Fiona-1.8.21-cp39-cp39-win_amd64.whl"}
