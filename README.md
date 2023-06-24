This repository contains large files and binaries that are used in documentation etc.

The files are hosted at https://github.com/opencdms/http://assets.opencdms.org/
and are served at https://assets.opencdms.org

To update the HTML index files run:
```
python3 -m venv html-index2
cd html-index2
. bin/activate

git clone https://github.com/isedwards/html-index
pip install -e html-index

# Change to the directory that you want to create HTML index files for
# Create a .indexignore file containing filenames that you don't want included
index .

```
