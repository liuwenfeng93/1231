# 1231 Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/liuwenfeng93/1231 1231
cd 1231
make install
```

From pypi:

```bash
pip install 1231
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ 1231
```

or

```bash
$ python -m 1231
```

To see the help message and usage instructions.

## First run

```bash
1231 create-db   # run once
1231 populate-db  # run once (optional)
1231 add-user -u admin -p 1234  # ads a user
1231 run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
