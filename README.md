# printJSON
python library for prettifying, and printing dictionaries

## Usage

1. Clone this repository 
```bash
git clone https://github.com/PiciAkk/printJSON
```
2. Go to the directory, you just cloned
```bash
cd printJSON
```
3. Make a file, or start a Python shell in that directory
```bash
touch example.py
```
4. Import this module
```python
import printJSON
```
5. Write something to the screen
```python
printJSON.printJSON({"key": "value", "anotherkey": "anothervalue", "something": {"subkey": "subvalue"}})
```
6. Tada!

Output: 

```json
{
    "key": "value",
    "anotherkey": "anothervalue",
    "something": {
        "subkey": "subvalue"
    }
}
```
