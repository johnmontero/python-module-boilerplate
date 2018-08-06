Python Module Boilerplate
=========================
Proyecto para crear modules instalables en python

Instalar
--------
Mediante setup.py
```console
(venv) ~/python-module-boilerplate ❯❯❯ python setup.py install
Processing dependencies for module==0.0.1
Searching for marshmallow==2.15.3
Finished processing dependencies for module==0.0.1
```

Para instalar usando pip desde un repositorio en git, agregar al archivo requirements.txt:

```console
git+https://github.com/johnmontero/python-module-boilerplate.git
```

Instalar modo development
-------------------------
```console
(venv) ~/python-module-boilerplate ❯❯❯ python setup.py devlopment
Processing dependencies for module==0.0.1
Searching for marshmallow==2.15.3
Finished processing dependencies for module==0.0.1
```

Usar
----
```console
Python 3.7.0 (default, Jul 23 2018, 20:22:55)
[Clang 9.1.0 (clang-902.0.39.2)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> from module import get_version
>>> get_version()
'0.0.1'
>>>
```

Test
----
Instalar pytest
```console
(venv) ~/python-module-boilerplate ❯❯❯ pip install pytest
```

Ejecutar pytest -v
```console
(venv) ~/python-module-boilerplate ❯❯❯ pytest -v
```