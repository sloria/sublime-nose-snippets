Sublime Text Snippets - Python Nose Testing
===========================================

Sublime Text snippets for [nose](https://nose.readthedocs.org/en/latest/) testing.

Install
-------

### Package Control (the easy way)
Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control) if you don't have it.

In the command pallette (Cmd-Shift+P on Mac) type 'Install' then press enter to see a list of packages. Search for 'Python Nose Snippets' then press enter to install.

### ...OR copy files to your Packages directory.

#### Mac OS X
    git clone git://github.com/sloria/sublime-nose-snippets.git ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/Python/sublime-nose-snippets

#### Windows
    git clone git://github.com/sloria/sublime-nose-snippets.git %userprofile%\AppData\Roaming\Sublime Text 2\Packages\Python\sublime-nose-snippets


Examples
--------

- `_==` expands to `assert_equal(first, second)`
- `_~=` expands to `assert_almost_equal(first, second, places=7)`
- `_>` expands to `assert_greater(first, second)`
- `_raises` expands to `assert_raises(Exception)`
- `testcase` expands to:

```python
class MODULETest(unittest.TestCase):

    def setUp(self):
        pass

    def tearDown(self):
        pass

    def test_FEATURE(self):
        assert False, "Finish me."
```

All snippets
------------

- `_==` and `_!=`
- `_~=` and `_!~=`
- `_>`, `_>=`, `_<`, and `_<=`
- `_true` and `_false`
- `_in` and `_!in`
- `_is` and `_isnot`
- `_isnone` and `_isnotnone`
- `_isinstance` and `_!isinstance`
- `_raises`
- `_matches` and `_!matches`
- `testcase`
- `noseboiler` (unittest and nose imports + an example TestCase)

Licensed under the [WTFPL](http://www.wtfpl.net/).

