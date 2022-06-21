## AJAX

This repo contains the ADVI implementation in JAX. The original paper is [here](https://www.jmlr.org/papers/volume18/16-107/16-107.pdf).

### Installation

```
pip install git+https://github.com/patel-zeel/ajax.git
```

### Basic usage
```py
from ajax import Prior, Likelihood, Variational, ADVI
```

### Core Principals

* Each component in prior should return a single scalar `log_prob`.
