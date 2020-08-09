# World Clock Web App
This project is to enable users to generate time for any city/timezone of their choice, they can also add timezones of their choice to keep track of multiple times at once. 

## Built with
[Timezonedb  API](https://timezonedb.com/) - This is the API used to generate accurate time data for different Locations

## Thought Process
  [Timezonedb  API](https://timezonedb.com/) was used to generate all available timezones, when the user request for any timezones which is in the list of the available timezones returned, 
  a request is sent to the [API](https://timezonedb.com/) which returns an object containing needed time data including current time, country, timezone abbreviation amongst others. 
  this data generated is then parsed to desired format and displayedd to the user.

## Requirements not covered in submition 
We couldn't get any API to generate timezone for different cities(i guess that's because even some cities aren't documented), so we used a closer one, a timezone API that returns all timezones in the world. 

## Issues faced while completing this task
We couldn't figure out how to split task amongst ourselves, this was my fault though, this is my first internship and also the first time leading a team so i'm pretty new to the process

  So to get the app working, we went from deciding if we need an API to generate all timezones or we should simply hardcode all existing timezones(a lot of work) to deciding which API is the best to use.
We used one initially but it turned out that it does not respond to all request sent it(server problem I think), This took us some time before we discovered this was the reason
our app was crashing. We later found [Timezonedb  API](https://timezonedb.com/) which was used in the final build.

## Contributors
* **[Ebenezer](https://github.com/eb-kneezer)** 
* **[Odizee](https://github.com/odizee)** 
* **[Mutmainah](https://github.com/mutmainaho)** 
* **[Olubanke](https://github.com/Olubanke)** 
* **[Vivyanne](https://github.com/Vivyanne-504)** 
* **[Whayasay](https://github.com/Whayasay392)** 
* **[Ahmad](https://github.com/Ahma-dev)** 

## Acknowledgement 
[jQuery autocomplete Plugin](http://xdsoft.net/jqplugins/autocomplete)

[Mutmainah](https://github.com/mutmainaho) - Pointed out my lapses as the team lead, i really appreciate it. 


