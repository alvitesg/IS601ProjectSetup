# Homework 2 - Github Repository, Python Installation, and Pytests

## Github Repo with required setup and files
1. Files: readme.md; .gitignore; requirements.txt; pytest.ini
2. Folder with files: Calculator folder with init file; tests folder with init file and test-calculator file

	touch .gitignore
	touch readme.md
	touch pytest.ini
 	mkdir calculator
  	mkdir tests
  	touch calculator/__init__.py
  	touch tests/__init__.py
  	touch .pylintrc
 	touch pytest.ini
  	touch tests/test_calculator.py
	

## Python Installations

1. Installed virtual Python environment in my Project
2. Initiate local python
	source venv/bin/activate
2. Installed py tests
	pip install pytest
	pip install pylint-pytest
	pip install pytest-cov
2. Create requirements.txt file
	pip freeze > requirements.txt
	pip install -r requirements.txt (to install libraries to make projects work)

## Testing Runs on Code
1. pytest
2. pytest --pylint
3. pytest --pylint --cov
4. Review results and resolve errors until code has Passed.
