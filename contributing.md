https://betterscientificsoftware.github.io/python-for-hpc/tutorials/python-pypi-packaging/

python setup.py sdist
python setup.py bdist_wheel --universal
twine upload dist/*