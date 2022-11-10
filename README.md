# Building GUIs for Windows, Mac or Linux
## ... with Python, Flask, Django and TailwindCSS
## ... on a Windows machine.

#### Basic requirements

- Latest Python
- Latest NodeJS

#### Step by step setup

Create a folder:
```
$ mkdir your_folder
```

Enter the folder:
```
$ cd your_folder
```

Clone the repository (don´t forget the dot at the end!):
```
$ git clone https://github.com/dahas/python_gui_boilerplate.git .
```

Make sure Python is installed. Otherwise install it now: 
```
$ python --version
```

Create a virtual environment:
```
$ pip install virtualenv
$ python -m venv env
```

Activate the virtual environment:
```
$ .\env\Scripts\activate
```
*(To deactivate simply enter 'deactivate' in the console)*

Install dependencies:
```
$ pip install flask flaskwebgui pyinstaller firebase-admin
```

Export requirements (needed later):
```
$ pip freeze > requirements.txt
```

Install yarn:
```
$ npm install -g yarn
```

Install dependencies:
```
$ yarn install
```

Initialize TailwindCss:
```
$ yarn tailwindcss init
```

Run css watcher:
```
$ yarn watch
```

Run local webserver:
```
$ yarn run-app
```

Visit http://127.0.0.1:5000 in the browser to check the result.

#### Author
Martin J. Wolf

#### License
MIT