# Python
---
### 1. Binary File Operations

```python
import pickle

fp = open("E://test.dat","wb")
l = intput("Enter message")
pickle.dump(l,fp)
fo.close()
```

#### Output
```
Enter a Message : Hello World
```
### 2. Reading from Binary Files

```python
import pickle

fp = open("E://test.dat","rb")
l = pickle.load(fp)
print(l)
fo.close()
```
