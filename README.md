<!--
https://readme42.com
-->


[![](https://img.shields.io/pypi/v/import-env-file.svg?maxAge=3600)](https://pypi.org/project/import-env-file/)
[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/import-env-file.py/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/import-env-file.py/actions)

### Installation
```bash
$ [sudo] pip install import-env-file
```

#### Examples
`.env`
```python
DB_NAME="name"
...
```

`settings.py`
```python
import import_env_file
import os

DATABASES = {
    'default': {
        'NAME': os.getenv('DB_NAME'),
    }
}
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
