## OpenSSL

```bash
cd nginx/ssl
```
```bash
openssl genrsa > privkey.pem
```
```bash
openssl req -new -x509 -key privkey.pem > fullchain.pem
```