## NEWSAPI <div dir="rtl">10.09.2021</div>
#### <div dir="rtl">By **Mark Muchiri Macharia**</div>
## Description
This is an application that will help list and preview news articles from various sources.
## Deployed website 
This app is live @  
## How it works 
As a user can ;
* see various news sources on the homepage of the application.

*  select a news source and see all news articles from the selected news source in the application.

* see the image, description and the time a news article was created.

* click on an article and read the full article on the source website.

## Behavior driven devlopment (BDD)

| Intention        | Action               | Behaviour                                         |
| ---------------- |:--------------------:| -------------------------------------------------:|
| sources          |displays news sources | user is able to see news sources on the homepage  |
| click link       |navigates to article  | allows user to access the article                 |

## Installation

Installation for the package can be done via `pip`:

```bash
$ python -m pip install newsapi-python
```

## Usage

After installation, import the client class into your project:

```python
from newsapi import NewsApiClient
```

Initialize the client with your API key:

```python
api = NewsApiClient(api_key='XXXXXXXXXXXXXXXXXXXXXXX')
```

## Setup
* Clone this repo to your desktop
* run this in your terminal "git remove set-url" if you wish to have it into your repository
* create a directory for this project
* run "sudo add-apt-repository ppa:jonathonf/python-3.6" in your terminal to install python followed by "sudo apt-get update" , then "sudo apt-get install python3.6 ".
* install pip which is the flask package manager..
* run "pip install flask to install flask.
* run "atom ." or "code ." in you terminal depending on the text editor you wish to use.

## Known Bugs
No known bugs.

## Technologies Used
* Bootstrap 
* Flask framework that is a Python microframework.
* javascript
* awesome & google fonts

## Support and contact details
For feedback contact me through;
* mark.macharia@student.moringaschool.com
* 0759329269

[![License](https://img.shields.io/github/license/mattlisiv/newsapi-python.svg)](https://github.com/mattlisiv/newsapi-python/blob/master/LICENSE.txt)
[![PyPI](https://img.shields.io/pypi/v/newsapi-python.svg)](https://pypi.org/project/newsapi-python/)
[![Status](https://img.shields.io/pypi/status/newsapi-python.svg)](https://pypi.org/project/newsapi-python/)
[![Python](https://img.shields.io/pypi/pyversions/newsapi-python.svg)](https://pypi.org/project/newsapi-python)

### License
[MITlicense](LICENSE) 2021 **MARK MUCHIRI MACHARIA**