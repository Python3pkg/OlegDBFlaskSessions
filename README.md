OlegDBFlaskSessions
========================

Flask sessions stored in OlegDB.

To install:
```
python setup.py install
# or from pypi:
pip install oleg-flask-sessions
```


To use in your flask app:
```python
from olegsessions import OlegDBSessionInterface
...
app.session_interface = OlegDBSessionInterface()
```

make sure OlegDB is running somewhere.
