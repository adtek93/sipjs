Replace the WebRTC info in project/apps.js with your account

    // Khởi tạo SIPCreds
    if (typeof user === 'undefined') {
        user = JSON.parse(localStorage.getItem('SIPCreds')) || {
            User: 'your user',
            Pass: 'your pass',
            WSServer: 'wss://your domain:8089/ws',
            Display: 'your display',
            Realm: 'your realm',
            callDestination: 'sip:your-destination@your-wss'
        };
        localStorage.setItem('SIPCreds', JSON.stringify(user));
    }

Link Demo:
https://adtek93.github.io/webphone-sipjs/

<img width="421" height="770" alt="image" src="https://github.com/user-attachments/assets/f2070315-fa7d-430a-8d2d-a18fe8d3caff" />
