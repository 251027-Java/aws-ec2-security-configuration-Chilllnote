Given these symptoms, identify the likely cause:

| Symptom	| Likely Cause	| Solution|
|---------|---------------|---------|
Can't SSH to instance |	port 22 is not open to outbound requests or security key does not work for ssh	| fix key or allow all requests  |
Website not loading	| Either the ports are closed or the website server is down |	Create more fault tolerance for the server and/or send requets out to users so they can know when the servers are down |
API calls timing out	| Routes to API are corrupted or ill-defined. That or the firewall is caused the packets to not be allowed|	Define outbound requests better. On the userside, check your firewall |
