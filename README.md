# Celery-Tutorial
This is a Celery tutorial.

* [Video Link](https://youtu.be/THxCy-6EnQM)

Use this command to start Celery:
```
python3 -m celery -A tasks worker --loglevel=info
```

Open another terminal and run Python Shell, then enter the following:
```
from tasks import reverse
```

From here, you can run the following lines of code to observe how Celery works:
```
result = reverse.delay('SomeString')
result
result.status
result.get()
```