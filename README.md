## header-printer
Python package for printing a nicely formatted header.
### Installation
Run the following command to install:
```shell
pip install header-printer
```
### Usage
In you script import and use function  `print_header`.
```python
from header_printer import print_header

print_header('Some text') 
```
Header will be stretched to the full length of the terminal.
The provided text will be centered.
```shell

********************************************
                 Some text                  
********************************************

```
### Development
To install all dependencies required for local development, run:
```shell
make install-dev
```
