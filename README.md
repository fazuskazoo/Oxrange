{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Orange\n",
    "\n",
    "\n",
    "python setyp.py sdist  # dist/project.tar.gz\n",
    "python setup.py bdist-wheel # dist/proect.whl\n",
    "\n",
    "pip install .  # installs project.0.0.1\n",
    "\n",
    "\n",
    "* Installed gi with the following \n",
    "```\n",
    "https://pygobject.readthedocs.io/en/latest/getting_started.html#ubuntu-getting-started\n",
    "```\n",
    "* runs a root and follows venv path\n",
    "```\n",
    "source bin/activate\n",
    "sudo env \"PATH=$PATH\" python -m orange.orange\n",
    "```"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## DataCamp Tutorial\n",
    "https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "* Latex Example\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "$$c = \\sqrt{a^2 + b^2}$$"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {},
   "outputs": [
    {
     "data": {
      "text/latex": [
       "$\\displaystyle \\sqrt{a^2 + b^2}$"
      ],
      "text/plain": [
       "<IPython.core.display.Math object>"
      ]
     },
     "metadata": {},
     "output_type": "display_data"
    }
   ],
   "source": [
    "from IPython.display import display, Math, Latex\n",
    "display(Math(r'\\sqrt{a^2 + b^2}')) "
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": 3,
   "metadata": {
    "scrolled": false
   },
   "outputs": [
    {
     "data": {
      "application/json": {
       "cell": {
        "!": "OSMagics",
        "HTML": "Other",
        "SVG": "Other",
        "bash": "Other",
        "capture": "ExecutionMagics",
        "debug": "ExecutionMagics",
        "file": "Other",
        "html": "DisplayMagics",
        "javascript": "DisplayMagics",
        "js": "DisplayMagics",
        "latex": "DisplayMagics",
        "markdown": "DisplayMagics",
        "perl": "Other",
        "prun": "ExecutionMagics",
        "pypy": "Other",
        "python": "Other",
        "python2": "Other",
        "python3": "Other",
        "ruby": "Other",
        "script": "ScriptMagics",
        "sh": "Other",
        "svg": "DisplayMagics",
        "sx": "OSMagics",
        "system": "OSMagics",
        "time": "ExecutionMagics",
        "timeit": "ExecutionMagics",
        "writefile": "OSMagics"
       },
       "line": {
        "alias": "OSMagics",
        "alias_magic": "BasicMagics",
        "autoawait": "AsyncMagics",
        "autocall": "AutoMagics",
        "automagic": "AutoMagics",
        "autosave": "KernelMagics",
        "bookmark": "OSMagics",
        "cat": "Other",
        "cd": "OSMagics",
        "clear": "KernelMagics",
        "colors": "BasicMagics",
        "conda": "PackagingMagics",
        "config": "ConfigMagics",
        "connect_info": "KernelMagics",
        "cp": "Other",
        "debug": "ExecutionMagics",
        "dhist": "OSMagics",
        "dirs": "OSMagics",
        "doctest_mode": "BasicMagics",
        "ed": "Other",
        "edit": "KernelMagics",
        "env": "OSMagics",
        "gui": "BasicMagics",
        "hist": "Other",
        "history": "HistoryMagics",
        "killbgscripts": "ScriptMagics",
        "ldir": "Other",
        "less": "KernelMagics",
        "lf": "Other",
        "lk": "Other",
        "ll": "Other",
        "load": "CodeMagics",
        "load_ext": "ExtensionMagics",
        "loadpy": "CodeMagics",
        "logoff": "LoggingMagics",
        "logon": "LoggingMagics",
        "logstart": "LoggingMagics",
        "logstate": "LoggingMagics",
        "logstop": "LoggingMagics",
        "ls": "Other",
        "lsmagic": "BasicMagics",
        "lx": "Other",
        "macro": "ExecutionMagics",
        "magic": "BasicMagics",
        "man": "KernelMagics",
        "matplotlib": "PylabMagics",
        "mkdir": "Other",
        "more": "KernelMagics",
        "mv": "Other",
        "notebook": "BasicMagics",
        "page": "BasicMagics",
        "pastebin": "CodeMagics",
        "pdb": "ExecutionMagics",
        "pdef": "NamespaceMagics",
        "pdoc": "NamespaceMagics",
        "pfile": "NamespaceMagics",
        "pinfo": "NamespaceMagics",
        "pinfo2": "NamespaceMagics",
        "pip": "PackagingMagics",
        "popd": "OSMagics",
        "pprint": "BasicMagics",
        "precision": "BasicMagics",
        "prun": "ExecutionMagics",
        "psearch": "NamespaceMagics",
        "psource": "NamespaceMagics",
        "pushd": "OSMagics",
        "pwd": "OSMagics",
        "pycat": "OSMagics",
        "pylab": "PylabMagics",
        "qtconsole": "KernelMagics",
        "quickref": "BasicMagics",
        "recall": "HistoryMagics",
        "rehashx": "OSMagics",
        "reload_ext": "ExtensionMagics",
        "rep": "Other",
        "rerun": "HistoryMagics",
        "reset": "NamespaceMagics",
        "reset_selective": "NamespaceMagics",
        "rm": "Other",
        "rmdir": "Other",
        "run": "ExecutionMagics",
        "save": "CodeMagics",
        "sc": "OSMagics",
        "set_env": "OSMagics",
        "store": "StoreMagics",
        "sx": "OSMagics",
        "system": "OSMagics",
        "tb": "ExecutionMagics",
        "time": "ExecutionMagics",
        "timeit": "ExecutionMagics",
        "unalias": "OSMagics",
        "unload_ext": "ExtensionMagics",
        "who": "NamespaceMagics",
        "who_ls": "NamespaceMagics",
        "whos": "NamespaceMagics",
        "xdel": "NamespaceMagics",
        "xmode": "BasicMagics"
       }
      },
      "text/plain": [
       "Available line magics:\n",
       "%alias  %alias_magic  %autoawait  %autocall  %automagic  %autosave  %bookmark  %cat  %cd  %clear  %colors  %conda  %config  %connect_info  %cp  %debug  %dhist  %dirs  %doctest_mode  %ed  %edit  %env  %gui  %hist  %history  %killbgscripts  %ldir  %less  %lf  %lk  %ll  %load  %load_ext  %loadpy  %logoff  %logon  %logstart  %logstate  %logstop  %ls  %lsmagic  %lx  %macro  %magic  %man  %matplotlib  %mkdir  %more  %mv  %notebook  %page  %pastebin  %pdb  %pdef  %pdoc  %pfile  %pinfo  %pinfo2  %pip  %popd  %pprint  %precision  %prun  %psearch  %psource  %pushd  %pwd  %pycat  %pylab  %qtconsole  %quickref  %recall  %rehashx  %reload_ext  %rep  %rerun  %reset  %reset_selective  %rm  %rmdir  %run  %save  %sc  %set_env  %store  %sx  %system  %tb  %time  %timeit  %unalias  %unload_ext  %who  %who_ls  %whos  %xdel  %xmode\n",
       "\n",
       "Available cell magics:\n",
       "%%!  %%HTML  %%SVG  %%bash  %%capture  %%debug  %%file  %%html  %%javascript  %%js  %%latex  %%markdown  %%perl  %%prun  %%pypy  %%python  %%python2  %%python3  %%ruby  %%script  %%sh  %%svg  %%sx  %%system  %%time  %%timeit  %%writefile\n",
       "\n",
       "Automagic is ON, % prefix IS NOT needed for line magics."
      ]
     },
     "execution_count": 3,
     "metadata": {},
     "output_type": "execute_result"
    }
   ],
   "source": [
    "\n",
    "%lsmagic"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
