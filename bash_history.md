# .bash_history
## Initial commit
```shell
git init
git status
# edit .gitignore
git add .
git commit -m "Initial commit"
# Create repository
git remote add origin git@gitflic.ru:deviur/price-table-example.git
git push -u origin master
```
## Creating Flask Hello World application
```shell
pip install --upgrade pip
pip install flask
pip freeze > requirements.txt
# Create index.py, static, templates ...
export FLASK_APP=index.py
echo $FLASK_APP  # --> index.py
flask run  # Checking that everything is working and press Ctrl+C to exit.
# Do commit
git status
# edit .gitignore
git add .
git commit -m'Added hello world app'
git push
```
## Creating price-table bootstrap page
```shell
# Create signup.html, style.css. Change to the index.py.
git add .
git commit -m'Added price-table example'
git push
```