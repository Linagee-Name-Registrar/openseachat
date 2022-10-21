# openseachat

## Flow
1. User opens chat extension
2. User is directed to chat.linagee.vision to sign a message
3. Once message is signed the address, guid, expiration, and access token are stored on a server
4. Head back to the extension and it will listen for the registration event from the backend then log you in
5. Go to OS and there will be a badge on every item owned by a .og holder. by clicking this badge you can start a new chat thread about an opensea item
6. The wallet address on thre backend must match the __user_id on OS, and opensea_logged_out must equal false
7. Users an link their email to recieve notifications

Open issues
1. how to store messages and message data: decentralized vs centralized for poc
