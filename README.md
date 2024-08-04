# Setup Project

## Setup local.properties untuk HokbenCrewDevice dan HokbenClientKiosk
    signaling_server_url=http://<ip laptop, komputer atau server>:<port yg digunakan untuk signaling server>
    wsl_url=ws://<ip laptop, komputer atau server>:<port yg digunakan>
    client_device=<Merek device untuk client, muncul di aplikasi client ketika di jalankan untuk signaling server>
    crew_device=<Merek device untuk crew, muncul di aplikasi crew ketika di jalankan>

## setup .env untuk signaling server:
    PORT=3030 # atau port lain yang tersedia

## jalankan signaling server
```console
npm install
npm start
```
