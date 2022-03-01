<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel

```bash
cd ~/proyectos
```
```bash
git clone https://github.com/IFC303/laravel-app
```
```bash
cd laravel-app
```
```bash
docker run --rm -v $(pwd):/app composer install
```
```bash
cp .env.example .env
```
```bash
sudo chown -R $USER:$USER .
```

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

## Docker
```bash
docker-compose up -d
```