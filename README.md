# Scala for Beginners
A repository of Scala tutorial notebooks

### How To Use

1. For best results, we recommend installing the [Almond Scala kernel](https://almond.sh/). Installation instructions can be found [here](https://almond.sh/docs/quick-start-install).


2. Install Jupyter lab:

```
pip install jupyterlab
```
Fore more information on Jupyter Lab, click [here](https://github.com/jupyterlab/jupyterlab)

We have found that Jupyter Lab will result in a build error when using < Python 3. To help manage your Python versions, we recommend you install `pyenv`:

```bash
brew update
brew install pyenv
```

3. Clone this repository and `cd` into it:

```
git clone git@github.com:pcandoalmeida/scala-for-beginners.git
```

Then (if you're having issues with Jupyter Lab and Python) install a local version of Python that works with Jupyter Lab. Otherwise, proceed to Step 4.

```bash
pyenv install 3.8.0
```

And then:

```bash
pyenv local 3.8.0
```

4. Run JupyterLab:

```
jupyter lab
```

If all goes well, you will see the `LabApp` run in the shell and open up the notebook application in your default web browser.

### Contributing 🎉

If you want to suggest a correction, improvement or add something useful, fire over a PR and get involved! 
