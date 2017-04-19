# DSI Python Workshop, Part 2

_April 21st, 2017_

Second in a two-part series (part 1 is [here][part1]), the workshop will be an
interactive example of start-to-finish data analysis in Python.

[part1]: https://github.com/clarkfitzg/python_april_2017

The workshop is aimed at people who have some programming experience, but not
necessarily in Python. If you are unfamiliar with concepts like if-statements,
for-loops, and data frames, you may find the workshop hard to understand.

## Getting Started

__Before coming to the workshop, please install the software discussed here!__
Downloading and installing the software takes time, so if you try to do it
during the workshop you might not be able to keep up.

You'll need __Python 3__ and the following packages:

* __jupyter__
* __numpy__
* __pandas__
* __bokeh__
* __requests__
* __lxml__

Brief installation advice for each platform is listed below.

### Windows & OS X

On these operating systems, we recommend installing the __Python 3.6__ version
of [Anaconda]. Anaconda automatically handles system configuration and includes
the Python packages listed above. The full list of packages installed with
Anaconda is available [here][anaconda-pkgs].

After installing Anaconda, you can verify that the install worked correctly by
opening a system terminal and running this command:

```bash
jupyter notebook
```

This should open a new browser window (or tab) that shows the Jupyter notebook
dashboard. If this works, you can close the browser window and then enter
`Ctrl-C` in the terminal to quit the Jupyter notebook program.

[Anaconda]: https://www.continuum.io/downloads
[anaconda-pkgs]: https://docs.continuum.io/anaconda/pkg-docs

### Linux

On Linux, we recommend installing Python 3 and the required Python packages
through your distribution's package manager. Any Python packages that are not
available through your distribution can be installed from the system terminal
with

```bash
pip3 install PACKAGENAME
```

You may need to use your distribution's package manager to install `pip` before
running these commands.
