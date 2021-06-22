## TAdam

The Pytorch implementation of TAdam algorithm in：'A decreasing scaling transition scheme from Adam to SGD'
[https://arxiv.org/abs/2106.06749](https://arxiv.org/abs/2106.06749)

### Usage

```python
from tadam import TAdam
...
optimizer = TAdam(model.parameters(), lr=1e-3, iters=required, gamma=required, up_lr=0.3, low_lr=0.01)

#iters(int, required): iterations
#	iters = (testSampleSize / batchSize) * epoch
#
#gamma(float, required): scaling factor
#	eg. 10^(-2) = gamma^(iters/4)
```





The code will be uploaded as soon as possible

