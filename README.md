# gnuplot-py
A python wrapper around gnuplot for graphing lists in python (without X11 installed)
###Usage

```python
y=[0,1,2,3,4,5]
grapher = grapher(y)
for i in range(5000):
    grapher.append(randrange(-10,10))
    graph = grapher.getGraph()
    for line in graph:
        print line
    sleep(.01)
```
