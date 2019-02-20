# favorite_tools
Tools, packages and so on that I've used in my work and want to remember. 

..this started out as a list of libraries that I just didn't want to forget, but now I'm having fun remembering all the libraries that I've used and loved in the past :)

# Shell
- [bat](https://github.com/sharkdp/bat) - A cat(1) clone with wings.
- [imgcat](https://github.com/eddieantonio/imgcat) for iTerm2 - It's like cat but for images.
- [fish](https://fishshell.com/)

# Python

## Environment Management
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

## Data Structures
- [frozendict](https://pypi.org/project/frozendict/) - Immutable dictionary
- bson, in particular bson.json_util for easy serialization of `datetime` and `ObjectId` types

## Data Science
- pandas
- dask
- [dask-kubernetes](https://kubernetes.dask.org/en/latest/) - I used this to spin up clustres for in memory analysis of TB sized data, then shutting down the VMs after completion.
- jupiter

## Geospatial
- geopandas
- osmnx
- folium

## Plotting
- seaborn

## DB
- pymongo
- sqlalchemy
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

