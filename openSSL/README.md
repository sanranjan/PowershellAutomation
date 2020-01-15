# openSSL on Windows

## Install openSSL on windows using chocolety

`choco install openssl.light`

Once openSSL gets installed successfully, Open a new Powershell session and run below command 
to genrate key and certificate:

`openssl req -newkey rsa:4096 -nodes -sha256 -keyout host.key -x509 -days 1095 -out host.crt`

This will cerate a certificate "host.crt" and a ket "host.key"
