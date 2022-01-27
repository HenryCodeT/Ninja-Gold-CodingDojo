# Ninja-Gold-CodingDojo
### python - flask - fundamentals
### Install packages
* ```pipenv install flask```
* ```pipenv shell```
* ```pipenv server.py```
### sessions
* ```session["random"]``` 
* ```session["total"] ```
* ```session["date"] ```
* ```session["random_casino"] ```
* ```session["dict_append"]```
### dict
*  ```
   dict_append = {
        "random_number":session["random"],
        "random_casino":session["random_casino"],
        "stage":request.form["stage"],
        "date_time":session["date"]
        }```
### append method
* ```session["dict_append"].append(dict_append)```
