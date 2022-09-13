## Installation and run

Python 3.8 is recommended.
Python 3.7 through 3.10 are supported and tested.

TorchDynamo requires the latest development/nightly build of PyTorch or
building [PyTorch from source]. TorchDynamo also requires [functorch]
from the PyTorch repository.  The Makefile target `make setup_nightly_gpu`
contain the commands used by our CI to setup dependencies.

The [1.12 branch] contains an older snapshot of TorchDynamo that works
on PyTorch 1.12.  However, this is missing the latest features and
not recommended.

[PyTorch from source]: https://github.com/pytorch/pytorch#from-source
[1.12 branch]: https://github.com/pytorch/torchdynamo/tree/1.12
[functorch]: https://github.com/pytorch/pytorch/tree/master/functorch
[hosted on pypi]: https://pypi.org/project/torchdynamo/

Install all dependencies
```shell
npm i
```

Run in dev mode:
```shell
npm run dev
```

Buld production files:
```shell
npm run build
```
