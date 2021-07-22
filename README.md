```bash
pytest src/tests
```

### Error

```bash
ImportError while importing test module '/Users/andreasdaiminger/Desktop/example/src/tests/test_script.py'.
Hint: make sure your test modules/packages have valid Python names.
Traceback:
../../anaconda3/lib/python3.8/importlib/__init__.py:127: in import_module
    return _bootstrap._gcd_import(name[level:], package, level)
src/tests/test_script.py:1: in <module>
    from src.script import add
E   ModuleNotFoundError: No module named 'src'
```