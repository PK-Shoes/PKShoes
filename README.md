# PKSHOES
An applicaiton for reviewing parkour shoes

## Installation

1. create a `python3` virtualenv, e.g. using plain `virtualenv`:
```bash
virtualenv [destination-directory]
```
2. activate the virtualenv, e.g. in `bash` (`$PATH_TO_VIRTUALENV` is a placeholder):
```bash
. "$PATH_TO_VIRTUALENV/bin/activate"
```
3. install dependencies
```bash
pip install -r requirements.txt
```

In order to use the scripts/modules of this repo, activate the aforementioned virtualenv first.

4. create `config.json` file in the root directory. This file should have the following structure:
```
{
  "SECRET_KEY": "my secret key",
  "DB": {
      "NAME": "database name",
      "USER": "user name",
      "PASSWORD": "user password",
      "HOST": "database host",
      "PORT": "database port"
  }
}
```

## Development