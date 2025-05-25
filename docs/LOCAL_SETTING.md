Local Setting

https://github.com/neo4j-graphacademy/app-python

Learn how to interact with Neo4j from Python using the Neo4j Python Driver


```
python -m venv .venv  
.venv\Scripts\activate
pip install -r requirements.txt
```

```
pip install python-dotenv
pip install neo4j
pip install flask-restx
```


```
netstat -ano | findstr :7687
taskkill /PID 24924 /F
```


set FLASK_APP=api
set FLASK_ENV=development
flask run