# WIA Code JavaScript SDK

JavaScript SDK for WIA Code System - 9-digit address system

## Installation
```bash
npm install wia-code-sdk
```

## Usage
```javascript
const WIACode = require('wia-code-sdk');

// Convert GPS to WIA Code
const code = WIACode.encode(37.5665, 126.9780);
console.log(code); // "123-456-789"

// Convert WIA Code to GPS
const coords = WIACode.decode("123-456-789");
console.log(coords); // {lat: 37.5665, lng: 126.9780}
```

## Features
- GPS to WIA Code conversion
- WIA Code to GPS conversion
- Distance calculations
- Emergency code generation

## License
MIT
