# Justice Dept EOIR PDF
 Combines the Justice Department EOIR website located at https://www.justice.gov/eoir/eoir-policy-manual into a searchable PDF.
This allows a user to search the PDF for relevant keywords which is currently impossible on the website.

This project was created by Deborah Cho for her final project in Coding For Lawyers - Fall 2021 at Hawaii Richardson Law School with 
assistance from instructor Matthew Stubenberg.

## Set up
Download the git repo.

Create a virtual python environment (i.e. a venv folder) by running
```
python -m venv venv
```
Depending on your OS activate the virtual environment

```
#Windows
venv/scripts/activate
#Linux
source venv/bin/activate

```
Then install requirements from the requirements file.
```
pip install -r requirements.txt
```
Then run the file by runing main.py
``` 
python main.py
```

## ToDo
- Tests should be created to test whether the website has changed.
- The PDF could look cleaner
- Add a cover sheet explaining where this PDF came from.
- Add some try/except to catch bad request calls