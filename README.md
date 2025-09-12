# WIA Pin Code JavaScript SDK
JavaScript SDK for WIA Pin Code System - 9-digit address system

## Installation
```bash
npm install wia-pincode-sdk
Usage
javascriptconst WIAPinCode = require('wia-pincode-sdk');

// Convert GPS to WIA Pin Code
const code = WIAPinCode.encode(37.5665, 126.9780);
console.log(code); // "123-456-789"

// Convert WIA Pin Code to GPS
const coords = WIAPinCode.decode("123-456-789");
console.log(coords); // {lat: 37.5665, lng: 126.9780}
Features

GPS to WIA Pin Code conversion
WIA Pin Code to GPS conversion
Distance calculations
Emergency code generation

License
MIT
