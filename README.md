<h1 align="center">sushan-reactapp-flask</h1>

## Project overview

This project shows how to serve a simple react application with a flask server

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure that you have the following tools available on your machine;

- [Git](https://git-scm.com/) A distributed version control system
- [Python](https://www.python.org/) A general purpose programming language
- [node](https://nodejs.org/en/) A JavaScript runtime
- A tool to create isolated Python environments preferably [Virtualenv](https://virtualenv.pypa.io/en/stable/)
- [Pip](https://pypi.org/project/pip/) A tool for installing python packages
- [create-react-ap](https://create-react-app.dev/) A supported way of creating single-page React applications
- [yarn](https://www.npmjs.com/package/yarn) A package manager for javascript

### Installing

While in your preferred terminal;

Start by cloning the repository to your local machine

```bash
git clone https://github.com/learningdollars/sushan-reactapp-flask.git

cd sushan-reactapp-flask/
```

Make and activate a python virtual environment using `virtualenv`

```bash
virtualenv venv

source venv/bin/activate
```

With the virtual environment activated, install the project dependencies for the flask server

```bash
pip3 install -r requirements.txt
```

```bash
cd react-app/
```

```bash
yarn install
```

## Serving the application

You can start a local server by running

```bash
python3 main.py
```

## Built With

- [Flask](http://flask.palletsprojects.com/en/1.1.x/) -A python web framework
- [React](https://reactjs.org/) - A JavaScript library for building user interfaces

## Authors

See also the list of [contributors](https://github.com/learningdollars/sushan-reactapp-flask/graphs/contributors) who participated in this project.
