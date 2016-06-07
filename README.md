    cd myflask_project
    touch README.md
    ./setup.sh
    pip install markdown
    git init
    mkdir app
    mkdir app/static
    mkdir app/templates
    mkdir tmp
    vi __init__.py
    vi views.py
    touch run.py
    chmod a+x run.py
    ./run.py
    git status
    git add .
    git commit -m "Initial commit"
    git branch
