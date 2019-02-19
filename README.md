# favorite_tools
Tools, packages and so on that I've used in my work and want to remember. 

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

## Data Mining
- pandas
- dask

## Geospatial
- geopandas
- osmnx
- folium

## Plotting
- seaborn


## Testing
[flake8](https://pypi.org/project/flake8/) - My favorite linter. I find it easy to configure. 
[pytest-cov](https://pypi.org/project/pytest-cov/) - easy test coverage
[pytest-xdist](https://pypi.org/project/pytest-xdist/) - Run tests in parallel

## Other
- [tenacity](https://pypi.org/project/tenacity/) - Super useful library for retrying. I use it often with HTTP calls on unstable connections.

