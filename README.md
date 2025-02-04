# **STREAM SYNC**

A self-hosted media streaming server which can transmit locally stored media files over the internet to some other device.

### Screenshots:

-   Server

    ![Server](/public/img1.png)

-   Initial page
    ![Initial page](/public/img2.png)

-   Directory Page
    ![Directory page](/public/img3.png)

-   Media selection:
    ![Media selection](/public/img4.png)

-   Media playback
    ![playback](/public/img5.png)

### Demo Working 
https://github.com/user-attachments/assets/aba9db41-f6e0-45fd-b6a9-9f5d2b4d27b1    
    

### To start the frontend, run the following commands:

-   `cd client`
-   `npm i` or `yarn`
-   `npm start` or `yarn start`

### To start the server, run the following commands:

-   `cd server`
-   `npm i` or `yarn`
-   `npm start` or `yarn start`

### How to play media on other device?

-   First start the server on the device which has the media files, the server will let you know the local ip, public ip and port it is running on in the terminal.
-   Connect to the frontend, this can be started in any device. The address of the frontend would be in the terminal when you start it. By default it is `localhost:3000`.
-   Connect to the server using the frontend, **by default it uses port 3001**. If both device are on the same network then you can use Local IP to connect. If they are on different network then you will need to open the port(s) on the host device so that the other device can connect to it using Public IP.
-   On the next page, enter the **absolute path** of the folder which contains media and click on submit.
-   On the new page, you will need to select the media you want to play. It will play successfully if it is supported by your browser otherwise you will get an error.
