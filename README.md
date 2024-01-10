# Utilizing Github API to assess repository populatrity
By default this script uses Github API to retireve the top 20 repositories with more than 1,000 followers.
The top X repositories can be adjusted using yaml file (see below)

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

