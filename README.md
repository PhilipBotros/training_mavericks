# Setup environment

First clone the repo:

```git clone https://github.com/PhilipBotros/training_mavericks```

Create virtual python3 environment (Mac/Linux):

```
mkdir virtualenv && cd virtualenv
virtualenv -p python3 .
source bin/activate
```

Create virtual python3 environment (Windows):

```
mkdir virtualenv && cd virtualenv
virtualenv -p python3 .
\Scripts Activate
```

With the virtual environment activated in the terminal install the required packages (from the project root folder):

```pip install -r requirements.txt```

Alternatively install the required packages found in requirements.txt for your native python (guess only the statsmodel is new for most people), you can do this in your terminal by (again, from the project root folder):

```pip install -r requirements.txt```