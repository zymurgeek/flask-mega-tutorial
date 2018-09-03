All commands below are run from the `microblog` subdirectory.

# Installation
1. `source venv/bin/activate`
1. `pip install -r requirements.txt`
1. `flask db upgrade`

# Running
`flask run`

# Maintenance
## To update requirements
`pip freeze > requirements.txt`

## To update migrations
`flask db migrate -m "description of migration"`

## To view this file in HTML
1. cd ..
1. `grip`
