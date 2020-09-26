# Raspberry Pi E-paper Weather Display

**A weather display using Raspberry Pi Zero W, Waveshare e-paper, Open Weather Map API, and Python.**

## Version 1.0

### Setup

- You will need an API key from [OpenWeather](https://home.openweathermap.org/users/sign_up).
- Open 'weather.py' and replace **Key Here** with your API key at line 52.
- **Location** can be left as it is unless you want to add it to your display.
- Add your Lat and Lon. [LatLong.net](https://www.latlong.net) is a good resource.
- Line 176 includes a reminder for taking out the trash. Comment out if not needed.

### Note

*If you are not using a 7.5 inch display, you will want to replace 'epd7in5bc.py' in the 'lib' folder.*
*Other models can be found here: [Waveshare's Github](https://github.com/waveshare/e-Paper/tree/master/RaspberryPi%26JetsonNano/python/lib/waveshare_epd)*

### Credit

*Icon designs are originally by [Erik Flowers](https://erikflowers.github.io/weather-icons/)*

### Licensing

*Weather Icons licensed under [SIL OFL 1.1](http://scripts.sil.org/OFL)*
*Code licensed under [MIT License](http://opensource.org/licenses/mit-license.html)*
*Documentation licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0)*
