# one-time-secret-fast-api
A simple one time secret app built using Fast API 

### Installation steps

```
 python3.11 -m venv ./venv # Creating python virtual env  
 source ./venv/bin/activate # Activate venv
 
 pip install fastapi    # Install fast api 
 pip install --upgrade pip    # Upgrade pip if necessary 
 pip install "uvicorn[standard]" # install uvicorn for real time refresh  
 
 uvicorn main:app --reload # Run application using
 hit Ctrl+C # to kill application 
```

### References :

- https://fastapi.tiangolo.com/#example