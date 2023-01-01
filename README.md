# taiwan-weather-555

## Installation

'''bash
npm install --save taiwan-weather-555
'''

## Requirements

首先申請中央氣象局 open data 的帳號並得授權碼

## Sample Code

'''js
const TaiwanWeather = require('taiwan-weather-555');
(async () => {
let data = await TaiwanWeather(授權碼, '澎湖縣');
console.log(data);
})();
'''

# License

The MIT licence
