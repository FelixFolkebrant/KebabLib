python setup.py sdist
pip install .
python setup.py bdist_wheel --universal
twine upload dist/*


Update:

1. Remove all files in dist/ and .egg/
2. python setup.py sdist
3. pip install .
4. python setup.py bdist_wheel --universal
5. twine upload dist/*
6. Login (ChickenProMeister)