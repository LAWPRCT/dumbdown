# Build
```
python setup.py sdist bdist_wheel
```

# Upload test

```
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
```
