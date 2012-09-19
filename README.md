# Weather Underground

A simple Ruby wrapper for the Weather Underground API


## Usage

    w = WeatherUnderground::Base.new(API_KEY)

Forecast

    w.forecast('63108')

GeoLookup:

    w.geolookup('63108')

IP Geolocation:

    w.autoip('127.0.0.1')


# Author

Chris Oliver  
Website: [excid3.com](http://excid3.com)  
Email: <chris@excid3.com>   
Twitter: [@excid3](https://twitter.com/excid3)  