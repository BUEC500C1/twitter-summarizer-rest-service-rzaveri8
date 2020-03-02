# HW4 Part 2 EC500
By: Ruby Zaveri

## Main Exercise
Use Flask as your Web service platform and integrate your module to become a RESTful a system. 

## Step 1 
- Use flask as your web service platform 

## Step 2

Integrate your module to become a RESTful system

## Step 3 
Deploy your system to free AWS service: https://aws.amazon.com/free/?all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc

## Step 4
Develop a simple Web applicaiton to test your system, document your REST APIs on Github.

### Prerequisites

Setup your config /config.py file as shown

```
TWITTER_API_KEY = XXXXXXXXX
TWITTER_API_SECRET_KEY = XXXXXXXXXXXXXXXXXX
TWITTER_ACCESS_TOKEN = XXXXXXXXX
TWITTER_ACCESS_TOKEN_SECRET = XXXXXXXXXXXXXXXXXXXXXXXXXXX
```

### Installing

Install requirements
```
pip3 install -r requirements.txt
```

### Running the Program
Run the command
```
python3 api.py
```
Then navigate to http://127.0.0.1:5000/video/Tweeter_Handle_Here
Please make sure to put a twitter handle in the url or you will get an error. 

To track the progress of the API calls please go to http://127.0.0.1:5000/status


### Tests

To test the program run

```
pytest test_code.py
```
If you do not have a keys file the tests will not run as they test api outputs. 


## References
Reference 1:  https://palletsprojects.com/p/flask/ (Github:  https://github.com/pallets/flask )
Reference 2:  Flask-RESTFUL  (Github:  https://github.com/flask-restful/flask-restful )
