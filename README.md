# brb

A simple command line tool that notifies when a command is done

![OS X notification](http://cl.ly/VxU3/Screen%20Shot%202014-06-08%20at%2019.23.07.png)

Requirements
------------
Install node and npm:

http://nodejs.org

Installation
------------
Node.js needs to be installed: http://nodejs.org

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
