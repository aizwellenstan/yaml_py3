```python
import yaml_py3 as yaml

def read_yaml(path):
    u"""Read data from path as yaml format.
    """
    with open(path) as f:
        return yaml.load(f, Loader=yaml.Loader)
```