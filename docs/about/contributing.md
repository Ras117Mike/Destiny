# How to contribute
There are two ways you can contribute to this project:

1. Fork the repository and make pull requests with your edits or additions.
2. Submit an issue [here](https://github.com/Ras117Mike/Destiny2/issues) with details and we'll make the changes.

## Keep these in mind
* Keep things Alphabetized for easy browsing.
* Add items to their respective directories, new ones can be created as needed.
* Use proper file naming, ex: `ace_of_spades_exotic.md`
* Use proper page naming, ex: `Ace of Spades: exotics/ace_of_spades_exotic.md`

## MkDocs
We use MkDocs and Material for MkDocs for this site. If you want to contribute, you will need to install it and some packages to keep things uniform.

### Prerequisits

Ensure that you have Python and pip installed on your system. I use Python 3 on a Mac, fyi.

```
$ python3 --version
Python 3.7.5
$ pip3 --version   
pip 19.3.1 from /usr/local/lib/python3.7/site-packages/pip (python 3.7)
```

### Installing MkDocs
```
pip3 install mkdocs
```

Check that everything worked
```
$ mkdocs --version
mkdocs, version 1.0.4 from /usr/local/lib/python3.7/site-packages/mkdocs (Python 3.7)
```

!!! note

    The above commands may not work if you are on Windows, use the `-m` option when you run them if you have issues. Example:
    ```
    python3 -m pip install mkdocs
    ```

### Installing Material

```
pip install mkdocs-material
```

Append the following line to your project's `mkdocs.yml`:
```
theme:
  name: 'material'
```
