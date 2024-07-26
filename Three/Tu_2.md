### Python实现wordcount
#### 如下代码
```python
text = """
Got this panda plush toy for my daughter's birthday,
who loves it and takes it everywhere. It's soft and
super cute, and its face has a friendly look. It's
a bit small for what I paid though. I think there
might be other options that are bigger for the
same price. It arrived a day earlier than expected,
so I got to play with it myself before I gave it
to her.
"""

def wordcount(text):
    fast = text.lower().replace('.',' ').replace(',',' ').replace('\n',' ').replace("'s",' is').split(' ')
    wein = ','.join(fast)
    print(wein)
    tabd = {'hello': wein.count('hello'), 'world': wein.count('world'), 'this': wein.count('this'), 'is': wein.count('is'), 'an': wein.count('an'), 'example': wein.count('example'), 'word': wein.count('word'), 'count': wein.count('count'),'fun': wein.count('fun'), 'it': wein.count('it'), 'to': wein.count('to'), 'words': wein.count('words'), 'yes': wein.count('yes')}
    print(tabd)
    
wordcount(text)
```
