# Utilizing Github API to assess repository populatrity
By default this script uses Github API to retireve the top 20 repositories with more than 1,000 followers.
The top X repositories can be adjusted using yaml file (see below)

## Instructions
```
#Install ghapi
pip install ghapi

#run pytest
pytest

#you should see
#====================================== test session starts ========================================
#platform linux -- Python 3.10.12, pytest-7.4.4, pluggy-1.3.0
#rootdir: /content
#plugins: anyio-3.7.1
#collected 2 items
#test/test_ghapi_func.py ..                                                                   [100%]
#======================================== 2 passed in 1.21s =========================================

```


## Input:
By default the code prints the top 20 repositories with results more than 1000 followers
*optional* config.yml file can be provided with key:value pair top_n: interger
There is a warning when more than 20 repositories is selected
- example config.yml:
```
top_n: 15
```
## output:
bar plot of top x repositories

