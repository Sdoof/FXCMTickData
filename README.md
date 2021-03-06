# FXCMTickData
Enjoy free access to our historical Tick Data.

Our repository contains Tick Data from 4 January 2015. The data is compiled by trading instrument for that trading week. The files are stored in our public directory and is updated every Monday.

https://tickdata.fxcorporate.com/{instrument}/{year}/{int of week of year}.csv.gz

    Instrument: 
                  AUDCAD, AUDCHF, AUDJPY, AUDNZD, CADCHF, EURAUD,
                  EURCHF, EURGBP, EURJPY, EURUSD, GBPCHF, GBPJPY,
                  GBPNZD, GBPUSD, NZDCAD, NZDCHF, NZDJPY, NZDUSD,
                  USDCAD, USDCHF, USDJPY

    Year:         2015, 2016, 2017, 2018

    Week:         1 to 52/53

To give an example, the path for extracting EURUSD data for the 1st week of 2015 would be

https://tickdata.fxcorporate.com/EURUSD/2015/1.csv.gz

If you are familiar with Python, we have two scripts that you may use for [Python 2.7](https://github.com/FXCMAPI/FXCMTickData/blob/master/TickData27.py) and [Python 3.4](https://github.com/FXCMAPI/FXCMTickData/blob/master/TickData34.py)


## Note:

•	For personal use only

•	Timestamps are in UTC

•	Data points are indicative and based on the our lowest spreads available exclusively on Active Trade accounts
