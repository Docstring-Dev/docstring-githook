# docstring-githook

git post-merge hook for Docstring.

## Installation

* Clone repo, and symlink post-merge into your repo's `.git/hooks`.
* Get your API key from [Docstring](https://app.docstring.dev/)
* Create the config file at `~/.docstring/config.ini` with your API key inserted:

```ini
[global]
api_key = ...
```
