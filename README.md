# del-DS_Store-py

## Instalation

```sh
git clone https://github.com/3zbumban/del-DS_store-py.git
cd del-DS_store-py
pip install -r requirements.txt
```

## Usage

```sh
python del-DS_store-py.py --help
```

### Start from script location

```sh
python del-DS_store-py.py -c
python del-DS_store-py.py --current-dir
python del-DS_store-py.py --cwd
```

### Give path as an argument to the script

```sh
python del-DS_store-py.py -p <path>
python del-DS_store-py.py --path <path>
```

Example:

```sh
python del-DS_store-py.py -p "C:\example\dir"
python del-DS_store-py.py --path "C:\example\dir"

```