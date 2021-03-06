Installation
============

Open up your terminal and type `gem install trades` or `sudo gem install trades` if the former gives you errors.

Alternatively you can download the 'trades-x.x.gem' file (listed above) and install that using `gem install /path/to/trades-x.x.gem` (replace x.x).

You need to have [Ruby](http://ruby.about.com/od/tutorials/a/installruby.htm) and [RubyGems](http://rubygems.org/pages/download) (included by default) installed. To test if you've got Ruby installed, type `ruby -v` in your terminal. This should display a version number if Ruby is installed.

Trades is developed and tested on Ruby version **1.9.2**.

Usage
=====

	Usage: trades [options]

	Options:
	    -m, --market MARKET              Filter on MARKET
	    -c, --currency CURRENCY          Filter on CURRENCY
	    -l, --log [FILENAME]             Log the results to FILENAME
	        --no-color                   Plain text instead of output colorized
	        --markets                    Show a list of all markets
	        --currencies                 Show a list of all currencies
	    -h, --help                       Show this message


More info: https://github.com/britishtea/Trades

To filter on market, type `trades -m mtgoxUSD` in your terminal. Type `trades -m mtgoxUSD -m thUSD` to filter on multiple markets. Trades uses the same names for markets as Bitcoincharts uses, though Trades has some aliases built-in. 

To filter on currency, type `trades -c USD` in your terminal. Type `trades -c USD -c EUR -c GBP` to filter on multiple currencies.

To log the results to a file, type `trades -l /location/trades.log` in your terminal. If no file is given, Trades will create a logfile in /var/log/. You can use this option in combination with one of the filtering options.

License
=======

All data is provided by [Bitcoincharts.com](http://bitcoincharts.com/). As long as you don't sell Trades for monies (or bitcoins!) you can do anything you want with it, except for rape.

Donations: 1PfTKrqoZpi9iUQVEqmCQTKkbXEGPNrypj 