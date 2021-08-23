# Homebrew Python2

## Why?
To have a following `Brewfile` possibility:

```
tap 'pchuri/homebrew-python2'
brew 'pchuri/python2/python@2.7.17', args: ['build-from-source']
```

## How do I install this formula?
`brew install pchuri/python2/python@2.7.17 --build-from-source`

Or `brew tap pchuri/python2` and then `brew install python@2.7.17 --build-from-source`.

## Limitations
As unsupported packages do not have bottles we need to install from
source. This has been tested on macOS 10.13 so far.

## Documentation
`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## References
- https://stackoverflow.com/questions/60298514/brew-reinstalling-python2
- https://docs.python-guide.org/starting/install/osx/
