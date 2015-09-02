# usertime.js
A jQuery plugin provides to display time in user's timezone.

## Download
[Compress](https://raw.github.com/emn178/usertime.js/master/build/usertime.min.js)  
[Uncompress](https://raw.github.com/emn178/usertime.js/master/src/usertime.js)

## Demo
[Demo](http://emn178.github.io/usertime.js/samples/demo/)

## Usage
HTML
```HTML
<usertime format="{format}">{time}</usertime>
```

#### *time: `String`*

Render server timestamp or string in any JavaScript Date acceptable format.

#### *Datetime Format: `String` (default: `YYYY-MM-DD HH:mm:ss`)*

Time format bases on moment. See [moment.format](http://momentjs.com/docs/#/displaying/format/).

## Example
HTML
```HTML
<usertime>1441099707112</usertime>
<usertime>2015-09-01T09:28:27+00:00</usertime>
<usertime format="lll">1441099707112</usertime>
```

## License
The project is released under the [MIT license](http://www.opensource.org/licenses/MIT).

## Contact
The project's website is located at https://github.com/emn178/usertime.js  
Author: emn178@gmail.com
