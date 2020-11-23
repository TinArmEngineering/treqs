	Some supplementary text

	[requirement id=REQ223 story=US10,US20]
	Requirement text
	[/requirement]

	More supplementary text

```python
for i in range(10):
    print(i)
```

```python
from IPython.display import display, Markdown, Latex
test_voltage = 100
display(Markdown("""[requirement id=REQ223 story=US10,US20]
The voltage must be >= {test_voltage}
[/requirement]""".format(test_voltage=test_voltage)))
```

```python
!treqs
```

```python
cd ..
```

```python

```
