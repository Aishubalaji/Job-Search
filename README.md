# Job Search

### https://job-search-flask.herokuapp.com/

A simple application that scrapes job postings from indeed and exports them as a xlsx file

#### Tools used:
- Heroku : For deployment
- Amazon s3 : For file storage

#### Run in local machine:
1. Create an Aws account and a Bucket
- Replace Access key, Access id, Bucket name with the details from your account in ````jobscraper.py```` 
2. Run ````python -m pip install -r requirements.txt```` to install the required packages
3. Run ````python app.py```` to run the application
4. Open ````http://127.0.0.1:5000/```` in your browser to view the application
