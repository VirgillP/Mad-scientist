# Mad-scientist
degrees with js
//kelvin degrees this doesn't change
const kelvin = 293;
console.log(kelvin);
//converting kelvin to celcius by substacting 273
let celsius = kelvin;
celsius -= 273;
console.log(celsius);
//converting celius to fahrenheit with this equation
let fahrenheit = celsius *(9/5)+32;
//rounding the number with floor Math
fahrenheit = (Math.floor(fahrenheit));
console.log(fahrenheit);
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit`);
//extra practice with newton
let newton = celsius*(33/100);
console.log(Math.floor(newton));
        
