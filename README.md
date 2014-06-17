# brb

A simple command line tool that notifies when a command is done

![OS X notification](http://cl.ly/VxU3/Screen%20Shot%202014-06-08%20at%2019.23.07.png)

Requirements
------------

* Mac OS X (>= 10.8)
* Linux with the notify-send module
* Or Growl on Windows

If using Linux, notify-send must be installed on your system. However, terminal-notifier, comes bundled in the module. So on Mac, not additional installations is necessary.

If using Windows/Growl, growl must be installed. For windows see Growl for Windows. You can also use growl on mac, but you need to specify this manually (see API).

By default Notification Center will be used on Mac, notify-send will be used on Linux, and Growl will be used if neither mac or linux.

Install node and npm:

http://nodejs.org

Installation
------------

    $ npm install -g brb

## Usage

	$ sleep 3; brb
	
	$ sleep 3 && brb
	
	$ bundle install
	Installing...
	brb

## Contributing

1. Fork it ( https://github.com/vikfroberg/brb/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
