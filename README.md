**Activate the virtual environment**

```
.\venv\Scripts\activate
```

**Install all packages**

```
pip install  -r requirements.txt
```

**Run the tests**
!!! Make sure the virtual environment is activated

```
python -m pytest backend/tests
```

**Run the application and API**
!!! Make sure the virtual environment is activated

```
python -m backend.app
```

**Run a peer instance**
!!! Make sure the virtual environment is activated

```
set "PEER=True" && python -m backend.app 
```

**Run the frontend**
```
npm run start 
```

**Seed_Data**
!!! Make sure the virtual environment is activated

```
set "SEED_DATA=True" && python -m backend.app 
```