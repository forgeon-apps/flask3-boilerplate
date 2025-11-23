Hehe, we wrote the spell, now we cast it 🧙‍♂️🔥

Assume your file is named `index.py`. Here’s the full run ritual:

---

### 1. Go to the project folder

```bash
cd /path/to/your/flask-playground
# e.g.
# cd ~/Documents/workspace_byeblogs/forgeon-demo-project/flask-example
```

---

### 2. Create a virtualenv (once)

```bash
python3 -m venv .venv
```

---

### 3. Activate the venv

```bash
source .venv/bin/activate
```

You should see something like:

```bash
(.venv) ➜ flask-playground %
```

---

### 4. Install Flask

If you don’t have a `requirements.txt` yet:

```bash
pip install Flask
```

(Optional) Freeze it:

```bash
pip freeze > requirements.txt
```

---

### 5. Run the app

Because we added:

```python
if __name__ == "__main__":
    app.run(host="0.0.0.0", port=5000, debug=True)
```

you just do:

```bash
python ./api/index.py
# or
python3 ./api/index.py
```

You should see something like:

```text
 * Serving Flask app 'app'
 * Debug mode: on
 * Running on http://127.0.0.1:5000
```

---

### 6. Visit it

Open browser:

* `http://127.0.0.1:5000/` → home card
* `/info`, `/about`, `/framework` → other HTML pages
* `/status` → JSON health
* `/v1` → JSON index

---

### 7. Stop + deactivate

* Stop server: `Ctrl + C`
* Leave venv when you’re done:

```bash
deactivate
```

If you tell me where you put the file (path), I can even write the exact commands tailored to your folder.
