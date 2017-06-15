# fanficsme-api
A simple passive API to [fanfics.met](http://fanfics.me/) using Python 3 and BS4
### Dependencies
* [Beautiful Soup 4](http://www.crummy.com/software/BeautifulSoup/)
* [requests](https://pypi.python.org/pypi/requests)
* [html5lib](https://github.com/html5lib)
### Setup
Install dependencies manually or using pypi:
```
  pip install bs4
  pip install html5lib
```
Clone or download the zip and import the module into your script
### Features
* Gather story information using the Story class with link or id
* Gather chapters using the Chapter class with direct link or specify story id and chapter's number
