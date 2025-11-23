# SimpDB

SimpDB is a simple key value database that stores JSON data, written in Python.

## Getting Started

### Installation

Clone the repository:

```shell
git clone https://github.com/ElliottStorey/simp-db.git
cd simp-db
```

### Usage

Import the module:

```python
from simpdb import SimpDB
```

Initialize a database:

```python
myDatabase = SimpDB("./myDatabase.sdb")
```

Set key-value pairs:

```python
myDatabase.set("username", "ElliottStorey")
myDatabase.set("password", 314159)
```

Read values:

```python
username = myDatabase.read("username")
print(username)  # Output: ElliottStorey
```

Delete keys:

```python
myDatabase.delete("username")
myDatabase.delete("password")
```
