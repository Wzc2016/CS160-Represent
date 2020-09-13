
# Represent!

Simple example of using the Google GEO API and CIVIC API to lookup Senate and House Representatives. You will need to use these API calls within Android Studio for PROG02 assignment.  This serves as an example of how the calls function and how to parse the JSON results. This should help get you started. Please note that this code does not handle all errors properly.  

## Getting Started

Python example of using Google Civic API and GEo API. You will need to have your own KEY to properly use the API. Instructions on Piazza for how to set that up.

* Setup your Google Cloud APIs
* Make a new Project for all CS160 Stuff
* You need to [enable Billing](https://console.cloud.google.com/project/_/billing/enable) to use the free CS160 credits 

### Prerequisites

* pip install requests – for making HTTP requests in Python
* [Google CIVIC API](https://developers.google.com/civic-information) - Used to lookup representatives
* [Google GEO API](https://developers.google.com/maps/documentation/geocoding/overview) - Used for GEO and reverese GEO lookups

### Example

Typical output:

```
Represent!

Berkeley, CA
U.S. Senators
   Dianne Feinstein [D] (202) 224-3841 https://www.feinstein.senate.gov/
   Kamala D. Harris [D] (202) 224-3553 https://www.harris.senate.gov
U.S. Representative
   Barbara Lee [D] (202) 225-2661 https://lee.house.gov/
 
New York, NY
U.S. Senators
   Charles E. Schumer [D] (202) 224-6542 https://www.schumer.senate.gov/
   Kirsten E. Gillibrand [D] (202) 224-4451 https://www.gillibrand.senate.gov/
 
Caldwell, TX
U.S. Senators
   Ted Cruz [R] (202) 224-5922 https://www.cruz.senate.gov/
   John Cornyn [R] (202) 224-2934 https://www.cornyn.senate.gov/
U.S. Representative
   Bill Flores [R] (202) 225-6105 https://flores.house.gov/
 
Budaghers, NM
U.S. Senators
   Martin Heinrich [D] (202) 224-5521 https://www.heinrich.senate.gov/
   Tom Udall [D] (202) 224-6621 https://www.tomudall.senate.gov/
U.S. Representative
   Debra Haaland [D] (202) 225-6316 https://haaland.house.gov/
 
Luxora, AR
U.S. Senators
   Tom Cotton [R] (202) 224-2353 https://www.cotton.senate.gov/
   John Boozman [R] (202) 224-4843 https://www.boozman.senate.gov/
U.S. Representative
   Rick Crawford [R] (202) 225-4076 https://crawford.house.gov/
```

## Authors

* [Eric Paulos](http://www.paulos.net)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* For UC Berkeley CS160 Fall 2020 Course

