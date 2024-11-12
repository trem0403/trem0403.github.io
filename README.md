A fork of [_traichu by Trssley](https://github.com/Tressley/_traichu).

⚠️ **You will need to generate your own OpenWeather API key!**
1. [Register for an OpenWeather account](https://home.openweathermap.org/users/sign_up) (OpenWeather will generate a default API key)
2. Sign in and navigate to Username > API keys and copy the key
3. Paste the key into [`line 10`](https://github.com/Tressley/Laputa/blob/3f2d695a4677f2a99c2c112fd11d01d71d6a05e9/js/main.js#L10) of `main.js`

**How to update your city**
1. Find your city using [OpenWeather's search](https://openweathermap.org/find)
2. Copy the city ID from the end of the URL
> `https://openweathermap.org/city/1850147` 🠆 `1850147`
3. Paste the city ID into [`line 26`](https://github.com/Tressley/Laputa/blob/3f2d695a4677f2a99c2c112fd11d01d71d6a05e9/js/main.js#L26) of `main.js`
