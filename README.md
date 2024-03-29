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

# Git
- [gitup](https://gitup.co/) - GUI for git, also visualizes branches nicely
- [redate](https://github.com/PotatoLabs/git-redate) - useful if system time was wrong when comitting
- [BFG Repo Cleaner](https://rtyley.github.io/bfg-repo-cleaner/) - for finding and removing large files and passwords comitted to git 

# Shell
- [bat](https://github.com/sharkdp/bat) - A cat(1) clone with wings.
- [imgcat](https://github.com/eddieantonio/imgcat) for iTerm2 - It's like cat but for images.
## Fish
- [fish](https://fishshell.com/)
- [Oh My Fish package manager](https://github.com/oh-my-fish)
- [bobthefish theme](https://github.com/oh-my-fish/theme-bobthefish)
- [plugin-git](https://github.com/jhillyerd/plugin-git)
- [chatgpt-prompt-wrapper](https://github.com/rcmdnk/chatgpt-prompt-wrapper)
- [zsh rocketship](https://github.com/spaceship-prompt/spaceship-prompt)

## zsh
- oh my zsh
- [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md)
- [history](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/history)

## AWS
- [aws-shell](https://github.com/awslabs/aws-shell)
- [awslogs](https://github.com/jorgebastida/awslogs) Much easier than having to use `aws-shell` or the AWS GUI
- [saw](https://github.com/TylerBrock/saw) Much like `awslogs`, but has a handy `watch` feature. 

# Hosted Services
## AWS
- EC2
- Lambda
- S3
- RDS (Aurora)
- DynamoDB
- ElastiCache (Redis and memcached)
- DocumentDB
- Redshift
- VPC
- CloudFront
- Route 53
- API Gateway
- CodeBuild
- CodeDeploy
- CodePipeline
- CloudWatch
- CloudFormation
- CloudTrail
- IAM
- Cognito
- Secrets Manager
- Key Management Service
- AWS Amplify
- AppSync
- Simple Queue Service
- Elastic Container Registry
- aws batch

## GCE
- bigquery

# Cloud Infrastructure
- Terraform
- [AWS Amplify](https://aws.amazon.com/amplify/) - great for quick prototyping, although gets tricky if you try to do stuff not in the docs. 
- brainboard

# Frontend
- [Material UI](https://material-ui.com/)

# Python

- [prebaked lambda layers](https://github.com/keithrozario/Klayers/blob/master/deployments/python3.8/arns/ap-northeast-1.csv)

## Environment Management
- [pyenv](https://github.com/pyenv/pyenv)
  - [pyenv virtualenv](https://github.com/pyenv/pyenv-virtualenv)
- ~pipenv~ R.I.P 🧟🧟🧟 
 - pipdeptree - I use this when resolving dependency issues in pipenv
- [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) - makes it super easy to switch between virtualenvs
- [autoenv](https://github.com/inishchith/autoenv) and [autoenv_fish](https://github.com/loopbit/autoenv_fish)
- [direnv](https://github.com/direnv/direnv/wiki/Python)
 
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
- [jupytext](https://github.com/mwouts/jupytext)
- awswrangler
- [papermill](https://papermill.readthedocs.io/en/latest/)
- [pandas-profiling](https://pypi.org/project/pandas-profiling/)

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
- fastapi
- sqlmodel

## Testing
[flake8](https://pypi.org/project/flake8/) - My favorite linter. I find it easy to configure. 
[pytest-cov](https://pypi.org/project/pytest-cov/) - easy test coverage
[pytest-xdist](https://pypi.org/project/pytest-xdist/) - Run tests in parallel

## Linting and Type Checking
- [black](https://black.readthedocs.io/en/stable/) - Keeps the python code syntax clean and readable.
- [black for jupyter notebooks](https://github.com/drillan/jupyter-black)
- [isort](https://github.com/timothycrosley/isort) - Manages module import order
- [mypy](http://mypy-lang.org/) - static type checker. Remember to install [mypy language server](https://github.com/matangover/mypyls/releases/tag/0.26.1)
- [pycln](https://hadialqattan.github.io/pycln/#/) - auto remove unused imports

## Other
- [tenacity](https://pypi.org/project/tenacity/) - Super useful library for retrying. I use it often with HTTP calls on unstable connections.
- scoop - I used to use this to distribute workloads over clusters of machines in my lab. Probably outdated by now.
- [faker](https://faker.readthedocs.io/en/master/) I use this to create mock data for tests
- [hashids](https://hashids.org/python/)
- [tqdm](https://github.com/tqdm/tqdm) - progress bars in scripts printed to terminal
- [progressbar2](https://pypi.org/project/progressbar2/) - another progressbar library. I use it similarly to `tqdm`.
- [wget](https://pypi.org/project/wget/)
- [retry](https://pypi.org/project/retry/)

# Third Party Services
- Datadog - I use use datadog to monitor most of my deployed containers
- Sentry - Use it for services that contain a lot of state that's useful when debugging
- Apiary - Online parser and formatter of API Blueprint markup

# Other tools
Airflow
Docker
Kubernetes

# Firefox
- simple tab groups
- yomichan
- https everywhere
- Firefox multi-account containers
- uBlock origin
- facebook container, twitter container, amazon container, google container

# Reading and Documentation
- [Python 3 Patterns, Recipes and Idioms](https://python-3-patterns-idioms-test.readthedocs.io/en/latest/)

# Data engineering
* [Panderas](https://pandera.readthedocs.io/en/stable/index.html) - Python dataframe schema
* [Great Expectations](https://docs.greatexpectations.io/docs/) - Data validation, e.g. for ETL
* [dbt](https://www.getdbt.com/)
* [dolt](https://www.dolthub.com/)
* 

# CICD
- [Github action linter](https://rhysd.github.io/actionlint/)
