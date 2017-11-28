# Go-Extension
Install Golang vscode extension process  

If you don't have vpn, 
You maybe need this

----

## Usage
- Install Go Extension for vscode.
- Install [Proxifier](http://www.proxifier.com/).
- You need a shadowsock or vps.
- Close shadowsock connection.
- Config Proxy Servers in Proxifier. 
```  
    Profile->Proxy Servers  
    Add->Fill in Address(vps ip) and prot(generally,the default is 1080)
    Protocol-> SOCKS Version 5
    Fisrt click check then click ok
```  
- Config Proxification Rules.
```
    Click Add button use to add new rules
    On new rules page, click browse button in Applications tab use to select a application config new rules(now,select you vscode application address)
    Select server you created in Action tab then click ok
```  
- **Now don't open you ss connection, or else there could be mistakes.**  
- Open you vscode and new create go file then update golang extension. 
- wait a few minutes and finsih.

## Other  
- If you don't want long time connection vps in vscode, you can select Proxification Rules then vscode rule of action modified to **Direct**. 