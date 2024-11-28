# djangogirlstutorial

Copied over from `https://github.com/andreibenea/sdev-220/tree/main/module-4/django-tutorial` (Module 4).

Purpose is to allow easier deployment & updates to `www.pythonanywhere.com`.

## cloning

Run the following commands (Windows users may need to use `python` instead of `python3`):
1. `git clone git@github.com:andreibenea/djangogirlstutorial.git`
2. `cd djangogirlstutorial`
3. `python3 -m venv .venv`
4. `source .venv/bin/activate` (Mac) or `.venv\Scripts\activate` (Windows)
5. `python3 -m pip install -r requirements.txt`
6. `python3 manage.py migrate`
7. `python3 manage.py runserver`