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
--
Application:
Upon accessing the call link, the system will automatically initiate a call to a predefined destination. This application is intended for seamless embedding into websites.

Demo available at: https://adtek.io.vn
<img width="1791" height="391" alt="image" src="https://github.com/user-attachments/assets/7df33a2e-ca76-4323-bf9c-45f8d782db2d" />

Link Demo:
https://adtek93.github.io/webphone-sipjs/
<div style="display: flex; justify-content: center; gap: 10px;">
  <img src="https://github.com/user-attachments/assets/adfe260f-4262-4506-b835-7359dd7bf5f8" width="300" height="600" alt="image" />    
  <img src="https://github.com/user-attachments/assets/64656275-fa4e-4d54-900d-52e9a053e1ce" width="300" height="600" alt="image" />    
  <img src="https://github.com/user-attachments/assets/947df66c-297f-4379-adee-785786e1d580" width="300" height="600" alt="image" />    
  <img src="https://github.com/user-attachments/assets/9742dab9-029e-4578-9868-abaf74e63759" width="300" height="600" alt="image" />    
</div>



