

## Install
Add this to your Dockerfile after setting your project's working directory:
```Dockerfile
RUN pip install zerorpc 
RUN pip install requests 
RUN wget https://raw.githubusercontent.com/empiricalci/empirical.py/master/empirical.py
```
