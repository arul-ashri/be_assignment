open the terminal and follow

```
git clone https://github.com/arul-ashri/be_assignment.git
```

```
cd be_assignment
```

```
python3 -m venv venv
```

```
source env/bin/activate
```

```
pip install --upgrade pip
```

```
pip install -r requirements.txt
```

```
export FLASK_APP=crudapp.py
```

```
flask db init
```

```
flask db migrate -m "entries table"
```

```
flask db upgrade
```

```
flask run
```
