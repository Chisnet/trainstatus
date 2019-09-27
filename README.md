# trainstatus
Access the London Tube and National Rail lines status in real-time from your terminal.

## Installation

### Dependencies
To run this script you will need to install [jq](https://stedolan.github.io/jq/download) 
- MacOS           `brew install jq`
- Ubuntu / Debian `apt-get install jq`

### Install
```sh
make install 
```
or
```sh
cp src/trainstatus /usr/local/bin/trainstatus
chmod 755 /usr/local/bin/trainstatus
```
## Running
Running is as easy as a simple `trainstatus` in the terminal.

Add either tube or rail to filter, e.g. `trainstatus tube`
