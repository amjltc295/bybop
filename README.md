# bybop : Bebop Drone control library for python

This is a non-officail library for python to control Bebop Drone, highly based on [Nicolas BRÛLEZ's bybop](https://github.com/N-Bz/bybop).

I pack the arsdk-xml submodule [here](https://github.com/amjltc295/arsdkxml).

Please tell me if this infringes the copy right.

## Prerequistes

* Python
* arsdkxml
* setuptool
* twine (for uploading)

## Installation

For latest version
```
python setup.py install
```

Pip install
```
pip install bybop
```

Upload to Pypi
```
python setup.py sdist
twine upload ./dist/<.tar.gz file>
```

## License

BSD

## Contributors

* [Nicolas BRÛLEZ](https://github.com/N-Bz) - *Initail commitment*
* [Ya-Liang Chang](https://github.com/amjltc295) - *Modification and packing*
