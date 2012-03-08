Weather Underground
===================

A simple Ruby wrapper for the Weather Underground API

Usage
-----

    w = WeatherUnderground::Base.new(API_KEY)

Forecast

    w.forecast('63108')

GeoLookup:

    w.geolookup('63108')

IP Geolocation

    w.autoip('127.0.0.1')

