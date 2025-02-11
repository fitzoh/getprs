# Gets PRs by Org and Team
Most of the time you want to be able to easily look at the PRs for your team so that they can be reviewed on an occasional basis. This application simplifies that by doing all the leg work for you.

# How to Install
Download the executable found in this repo

* MacOSX : [getprs](https://github.com/zendern/getprs/blob/master/distrubitions/getprs-darwin-amd64)
* Linux : [getprs](https://github.com/zendern/getprs/blob/master/distrubitions/getprs-linux-amd64)
* Windows (32) : [getprs.exe](https://github.com/zendern/getprs/blob/master/distrubitions/getprs-windows-386.exe)
* Windows (64) : [getprs.exe](https://github.com/zendern/getprs/blob/master/distrubitions/getprs-windows-amd64.exe)

Or build clone the repo and build it yourself for whatever platform you need.

# How to run it

Mac OSX
```
./getprs-darwin-amd64 <github api token> <organization> <team name> <optional output format>
```

Windows
```
getprs-windows-386.exe <github api token> <organization> <team name> <optional output format>
getprs-windows-amd64.exe <github api token> <organization> <team name> <optional output format>
```

## Where do i get this github api token thing??!?!?

See [here](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/) for a guide on how to do that 

# Screenshot

Table output (default)
![in action](https://github.com/zendern/getprs/blob/master/screenshots/table.png)

JSON output
![in action](https://github.com/zendern/getprs/blob/master/screenshots/json.png)

Text output
![in action](https://github.com/zendern/getprs/blob/master/screenshots/text.png)

