# To-Do API


An api that you can plan your day to day, writing your notes and obligations!

## Functionalities

- Create your user account
- Create, complete, delete to-dos
- See your to-dos
- Take control of your day list

## Api link

[API](https://to-do-api-hyan.herokuapp.com/)

## Documentation of api link

[DOCUMENTAÇÃO](https://to-do-api-hyan.herokuapp.com/api/documentation/)

## Running locally

Clone the project

```bash
  git clone git@github.com:To-Do-application/to_do_back_end.git
```

Enter the project directory

```bash
  cd to_do_back_end
```

Create your virtual enviroment

```bash
  python -m venv nameOfYourVirtualEnvironment
```

Activate your virtual environment

```bash
  source nameOfYourVirtualEnvironment/bin/activate
```

Install the dependencies

```bash
  pip install -r requirements.txt
```

Config your database settings with postgres: Open the file .env.example to see more details.

Run the migrations

```bash
  ./manage.py makemigrations
```

```bash
  ./manage.py migrate
```

Start the server

```bash
  ./manage.py runserver
```

## Stack used

**Back-end:** Python, Django-rest-framework


## My contacts


- [github](https://github.com/hyanlopes)
- [portifolio](https://hyan-portifolio.vercel.app/)
- [linkedin](https://www.linkedin.com/in/hyanlopes/)
