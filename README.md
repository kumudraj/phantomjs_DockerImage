## What is PhantomJS

[PhantomJS][phantomjs] is a headless WebKit browser, often used via [WebDriver][webdriver] for web system testing.
It's based on WebKit, runs JavaScript, and allows to take screenshots.

## Features of this image

This [Dockerized][docker] version of PhantomJS is:
* **Small**: Using ubuntu:18.04.
* **PhantomJS**: 2.1.1 install 
 
# Build Docker Images[PhantomJS2.1.1][Python3.6.9]
To pull pre build docker image[`pjs_py369`](https://hub.docker.com/repository/docker/kumudraj/pjs_py369):

$ docker pull kumudraj/pjs_py369:latest

# Installed packages
  * [`aiodns==2.0.0`, `aiohttp==3.6.2`, `aiohttp-swagger==1.0.14`]
  * [`async-timeout==3.0.1`, `lxml==4.5.1`, `bs4==0.0.1`, `psutil==5.7.0`]
  * [`requests==2.23.0`, `python-dateutil==2.8.1`, `html5lib==1.0.1`, `yarl==1.4.2`]
  * [`pyYAML==5.3.1`, `selenium==2.53.1`, `uvloop`, `gunicorn`]

[phantomjs]:        http://phantomjs.org/
[docker]:           https://www.docker.io/
[webdriver]:        http://www.seleniumhq.org/projects/webdriver/
