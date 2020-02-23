## How to create an HTTPS certificate for localhost domains
This focuses on generating the certificates for loading local virtual hosts hosted on your computer, for development only.  
**Do not use self-signed certificates in production !** For online certificates, use Let's Encrypt instead ([Tutorial](https://gist.github.com/cecilemuller/a26737699a7e70a7093d4dc115915de8)).
  
## Certificate authority (CA)
Generate <span style="background-color:green">RootCA.pem</span>, RootCA.key & RootCA.crt:  
