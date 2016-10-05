# National Contiguity Data and Flag Images 

These data are needed for building force directed graph.

The original `countries.json` file comes from this URL: <https://raw.githubusercontent.com/DealPete/forceDirected/master/countries.json>. It contains a minor error. It has a country called Yugoslavia which no longer exists with country code XK that belongs to Kosovo. The links however treat this country as Serbia, while Serbia as a country is absent from this file. So, I've changed Yugoslavia to Serbia and gave is Serbia country code, which is RS.

The second file is `flag_images.json` that contains the mapping from the country code to PNG image in `base64` format. This is needed so that I can easily embed these images into my force directed graph.

For details refer to this URL: <http://codepen.io/ellacodecamp/pen/pEdXJw>.