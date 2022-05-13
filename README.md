# NOTES

- `python3 -m venv venv` OR `py -3 -m venv venv` **Create an environment**
- `./venv/Scripts/activate` **Activate the environment**
- `pip install Flask` **Install Flask**
- `pip install flask-mysqldb` **Install ‘mysqlbd’ module in your venv**
- `pip install python-dotenv` **.env**
- `pip install pprint36` **var_dump debug**
- `./venv/Scripts/python app.py` **Launch Python Web Server**
- Database : **py_geekprofile**
- Serve on : http://127.0.0.1:5000/

```
if __name__ == "__main__":
    app.run(host="127.0.0.1", port=5000, debug=True)
```