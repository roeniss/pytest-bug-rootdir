# How to reproduce

```sh
git clone https://github.com/roeniss/pytest-bug-rootdir
cd pytest-bug-rootdir
pip install pytest
pytest --version # pytest 7.4.0
pytest -c settings/pytest.ini
```

You can see `settings/test/test_hello.py .`, which is not correct information.

