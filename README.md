# outliersdemo

### Installation
```python
pip install outliersdemo

```

### Usuage
```python
from src.main import find_outliers
import pandas as pd
import numpy as np

# Read your dataset here
data = pd.DataFrame(np.random.randn(1000, 4), columns=list("ABCD"))

print(find_outliers(data))

```