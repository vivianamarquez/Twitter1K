# Twitter 1K

```python
with open('../data/tweet.js') as f:
    file = f.read()
    file = file[file.find("["):]
    
data = json.loads(file)
df = json_normalize(data)
```
