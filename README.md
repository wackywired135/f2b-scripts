# Fail2Ban Scripts

Some useful (hopefully) scripts that can be used with Fail2Ban. This assumes that you have a working knowledge of linux.

## Installation

Obviously you need to have Fail2Ban installed and working.

### Install prerequisites
Install **python** and **pip**:
```
sudo apt-get install python-pip
```

Install Cloudflare:
```
pip install cloudflare
```

## Configuration

The following scripts can be edited to provide configuration:
 * [src/ignorecommands/dynamic-host](src/ignorecommands/dynamic-host)

If using the `cf-action` scripts, the api credentials can be added to your `action.d/cloudflare.local` file (see examples).

## Usage
See the [examples](examples) directory for more info.

## Authors
 * **[Zach Schneider](https://zacharyschneider.ca/)** - Initial work - @wackywired135

## History
 * 2016/11/06 - Initial commit (work in progress)

## License
Distributed under the MIT license. See the [`LICENSE`](LICENSE) file for more info.