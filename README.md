# InterCom

InterCom is a low-[latency](https://en.wikipedia.org/wiki/Latency_(engineering)) [full-duplex](https://en.wikipedia.org/wiki/Duplex_(telecommunications)#FULL-DUPLEX) intercom(municator) designed for the transmission of media (at this moment, only [audio](https://en.wikipedia.org/wiki/Digital_audio)) between networked users. It is implemented in [Python](https://www.python.org/) and designed as a set of layers that provide an incremental functionality, following a multilevel (one-to-one) [inheritance](https://en.wikipedia.org/wiki/Inheritance_(object-oriented_programming)) model.

## Install (if Python is already installed)

   pip install -r requirements.txt

### Python install

#### Linux

Python is already installed in Linux.

#### Visual Studio Code (all platforms)

See [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial#_install-a-python-interpreter).

### Jupyter-lab install

#### Linux (in a Python virtual environment)

     mkdir envs                # Only once
     cd envs                   # Only once
     python3 -m venv TM        # Only once
     source ~/TM/bin/activate  # Run this always you want to use the virtual environment
     pip install jupyter_lab   # Only once

#### Visual Studio Code (all platforms)

See [Jupyter Notebooks in VS Code](https://code.visualstudio.com/docs/datascience/jupyter-notebooks).

