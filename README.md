# Demo of HashiCorp Vault Agent feature that does auto-renewal of expiring TLS certificate on a nginx web server

This is using a Jupyter notebook to execute the steps required.
It also assumes that you have HashiCorp Vault installed and configured on your side.

You can use Visual Studio Code to run the notebook by:
- Installing "Jupyter" extension. Ref: https://www.alphr.com/vs-code-open-jupyter-notebook/
- Install the jupyter kernel for bash. Ref: https://pypi.org/project/bash_kernel/
```shell
pip install bash_kernel
python -m bash_kernel.install
```