# bash_scripts
Une collection de scripts bash

## `tunnelHTTP`

A simple script that open a webapp instance for a webapp acceded through boundary server.

### Configuration 

Add a tunnelHTTP.conf file with parameters :

- PROXY: Address of the boundary server
- USERNAME: Username used to connect to the boundary server
- BROWSER: name of your browser in the chrome/chromium family (this script use the flag --app to open an instance as a webapp)

### How to use it 

```bash
./tunnelHTTP <destination_server> <port>
```
