<h1>Library for clean screen of console</h1>
<hr>
Example:

```python
from cleanout import clean
from time import sleep

for i in range(10):
    print('------------------')
    print(f'------- {i} --------')
    print('------------------')
    
    sleep(1)
    clean()
```
