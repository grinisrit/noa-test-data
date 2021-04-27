# NOA: test artifacts

This is a repository for holding and versioning various artifacts used by the testing suite in the [NOA library](https://github.com/grinisrit/noa).

You can load the data into `python` to explore:
```python
import torch 
pumas_brems = list(torch.jit.load('pms/pumas_brems.pt').parameters())[0]
```

(c) 2021 Roland Grinis, GrinisRIT ltd.