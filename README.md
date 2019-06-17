# favorite_tools
Tools, packages and so on that I've used in my work and want to remember. 

..this started out as a list of libraries that I just didn't want to forget, but now I'm having fun remembering all the libraries that I've used and loved in the past :)

# Editors
## Atom
- [Vim Mode Plus](https://atom.io/packages/vim-mode-plus)
- [Atom Reindent](https://github.com/kbrose/atom-reindent)
- [Terraform syntax highlighting](https://atom.io/packages/language-terraform)
- [Terraform linting](https://atom.io/packages/linter-terraform-syntax)
- [Hydrogen](https://atom.io/packages/hydrogen) - Run code blocks like in Jupyter notebooks 
- [Pretty JSON](https://atom.io/packages/pretty-json)

## Vim
- Syntastic

# Shell
- [bat](https://github.com/sharkdp/bat) - A cat(1) clone with wings.
- [imgcat](https://github.com/eddieantonio/imgcat) for iTerm2 - It's like cat but for images.
- [fish](https://fishshell.com/) and [Oh My Fish](https://github.com/oh-my-fish), especially [bobthefish](https://github.com/oh-my-fish/theme-bobthefish)
- [aws-shell](https://github.com/awslabs/aws-shell)
- [awslogs](https://github.com/jorgebastida/awslogs) Much easier than having to use `aws-shell` or the AWS GUI
- [saw](https://github.com/TylerBrock/saw) Much like `awslogs`, but has a handy `watch` feature. 

# Cloud Infrastructure
- Terraform

# Python

## Environment Management
- [pyenv](https://github.com/pyenv/pyenv)
- pipenv
 - pipdeptree - I use this when resolving dependency issues in pipenv
 - virtualenvwrapper (not using recently, but it deserves a spot)
 
## Caching
- [cachetools](https://pypi.org/project/cachetools/) - Has a lot of useful caching decorators
- [async-lru](https://pypi.org/project/async_lru/) - Simple LRU caching for coroutines
- [asyncache](https://pypi.org/project/asyncache/) - Like `cachetools`, but supports coroutines

## Messaging
- [nameko](https://github.com/nameko/nameko) - Python framework for building microservices
- [pyzmq](https://pyzmq.readthedocs.io/en/latest/) - Probably my most favorite messagig library of all times.

## Job processing
- [python-rq](https://python-rq.org/docs/workers/)

## Data Structures
- [frozendict](https://pypi.org/project/frozendict/) - Immutable dictionary
- bson, in particular bson.json_util for easy serialization of `datetime` and `ObjectId` types
- [Python Sorted Containers](http://www.grantjenks.com/docs/sortedcontainers/)

## Data Science
- numpy
- pandas
- dask
- [dask-kubernetes](https://kubernetes.dask.org/en/latest/) - I used this to spin up clustres for in memory analysis of TB sized data, then shutting down the VMs after completion.
- jupiter

## Machine Learning
- https://github.com/benfred/implicit/
- Annoy

## Geospatial
- geopandas
- osmnx

## Plotting
- [bokeh](https://bokeh.pydata.org/en/latest/) - Great library for making streaming graphs and dashboards redered to javascript in the browser
- [brewer2mpl](https://pypi.org/project/brewer2mpl/) - useful little package with nice matplitlib compatible color maps
- folium
- matplotlib - lately there are so many high-level python plotting libs available, so I don't Matplotlib use so much. But it's the old grandfather, and I used to swear by it, so on the list it goes :)level details. 
- seaborn

## DB
- pymongo
- sqlalchemy
- ponyORM
- motor
- aioredis

## Web development
- flask
- aiohttp
- aiohttp-sentry

## Testing
[flake8](https://pypi.org/project/flake8/) - My favorite linter. I find it easy to configure. 
[pytest-cov](https://pypi.org/project/pytest-cov/) - easy test coverage
[pytest-xdist](https://pypi.org/project/pytest-xdist/) - Run tests in parallel

## Other
- [tenacity](https://pypi.org/project/tenacity/) - Super useful library for retrying. I use it often with HTTP calls on unstable connections.
- scoop - I used to use this to distribute workloads over clusters of machines in my lab. Probably outdated by now.
- [faker](https://faker.readthedocs.io/en/master/) I use this to create mock data for tests
- [black](https://black.readthedocs.io/en/stable/) - Keeps the python code syntax clean and readable.
- [isort](https://github.com/timothycrosley/isort) - Manages module import order

# Third Party Services
- Datadog - I use use datadog to monitor most of my deployed containers
- Sentry - Use it for services that contain a lot of state that's useful when debugging
- Apiary - Online parser and formatter of API Blueprint markup
