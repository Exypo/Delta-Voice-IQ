# Delta-Voice-IQ
Delta VoiceIQ API for homeassistant via Rest integration

Requirements: 

2 Secrets:
Both can be retrieved from https://device.legacy.deltafaucet.com/#/home

* delta_device_id - click on usage - it will be in the URL https://device.legacy.deltafaucet.com/#/device/usage/<your_device_id_here>
    delta_device_id: <your device id>
* delta_token 
    Go to inspector (Ctrl + Shift + I) -> Console;
    Type window.localStorage.auth_token a long string will come up. delta_token should be compiled as follows: 
       delta_token: Bearer <the string from above without quoted>
