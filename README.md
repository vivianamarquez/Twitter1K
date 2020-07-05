# Twitter 1K

```python
with open('../data/tweet.js') as f:
    file = f.read()
    file = file[file.find("["):]
    
data = json.loads(file)
df = json_normalize(data)
```

```python
for c in Counter(text_tere_clean).most_common():
    if list(pp.tag(c[0])[0])==['GivenName'] and not d.check(c[0]) and len(set(c[0])) != 2:
        if not d2.check(c[0]):
            print(c)
            
for c in Counter(text_vivi_clean).most_common():
    if list(pp.tag(c[0])[0])==['GivenName'] and not d.check(c[0]) and len(set(c[0])) != 2:
        if not d2.check(c[0]):
            print(c)
```
