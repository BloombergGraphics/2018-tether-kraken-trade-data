# 2018-tether-kraken-trade-data
Tether-USD transactions data used in the June 29, 2018



## Tether-USD Transactions Retrieved From the Kraken API

This repo contains data used in the June 29, 2018, story "[Crypto Coin Tether Defies Logic on Kraken's Market, Raising Red Flags](https://bloomberg.com/graphics/2018-tether-kraken-trades/)."

All data are Tether-USD transactions on Kraken from May 1 through June 22. The data used in this story were compiled by Bloomberg via the [Kraken API](https://www.kraken.com/help/api) on June 27. Bloomberg used the [krakenex](https://github.com/veox/python3-krakenex) Python 3 API client listed by [Kraken](https://www.kraken.com/help/api) and the [pykrakenapi](https://github.com/dominiktraxl/pykrakenapi) wrapper listed on the krakenex GitHub page to retrieve the data. Documentation is available on those GitHub pages.

The file in this repo reflects the data as pulled from the Kraken API, but Bloomberg News added an additional column to convert the UNIX timestamps into Greenwich Mean Time. The [datetime](https://docs.python.org/3/library/datetime.html) and [pytz](http://pytz.sourceforge.net/) Python modules were used to make that conversion.


## Attribution

The provided data should be cited as 'Data from the Kraken API obtained by Bloomberg News.'

If the data is used in an online story, the source line should include a link to this repository.