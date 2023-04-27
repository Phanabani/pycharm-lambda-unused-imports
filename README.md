# [`__init__.py` files under `lambda/` directories have imports marked as unused](https://youtrack.jetbrains.com/issue/PY-60375/init.py-files-under-lambda-directories-have-imports-marked-as-unused)

## Issue
When a directory is named `lambda`, all `__init__.py`files nested under it will have their imports marked as unused (screenshot 1).

## Expected result
Imports in `__init__.py` files should not be marked as unused, as is the usual behavior (screenshot 2, with the package name changed from `lambda` to something else).

## Reproduction repository
https://github.com/Phanabani/pycharm-lambda-unused-imports

## System details
PY-231.8109.197, JRE 17.0.6+10-b829.5x64 JetBrains s.r.o., OS Windows 11(amd64) v10.0 , screens 3840.0x2160.0
