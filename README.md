## Scrapy
Python Framework 
- Initial release : 26 June 2008
- Github repo : [Scrapy](https://github.com/scrapy/scrapy)
- [Scrapy Playbook](https://scrapeops.io/python-scrapy-playbook/)

## Commands
#### Activate venv
- poetry shell

#### Activate scrapy environment
- scrapy shell

#### Create a project
- scrapy startproject <project_name>

#### Create a spider 
- scrapy genspider <spider_name> <website_url>

#### Check we are in the right folder to run our spiders
- scrapy list

#### Save data to a file
- scrapy crawl <spider_name> -O <file_name>.csv
- scrapy crawl <spider_name> -O <file_name>.json