# ineryjs

# Inery Json RPC 4.Görev
Inery Blockchain'de JSON RPC'yi çağırmak


## 1) Başlayın
Eski Nodejs kaldırın
<br>

```shell
sudo apt-get remove nodejs
```

Curl'ü yükleyin

```shell
sudo apt-get install curl
```

Curl'ü yükleyin

```shell
    curl -fsSL https://deb.nodesource.com/setup_19.x | sudo -E bash - &&\
    sudo apt-get install -y nodejs
```

     
## 2) NPM kurulumu

```shell
sudo apt install npm
```



## 3) Kurulum

* Repoyu klonlayın

   ```
   git clone https://github.com/berfin21/ineryjs.git
   ```

* Dizine Girin

   ```
   cd ineryjs
   ```

* NPM Paket kurun

   ```
   npm install
   ```

* Aşağıdaki Kod ile env-sample dosyasının ismini .env yapın 

   ```
   cp .env-sample .env
   ```

*  ```.env``` bilgileriniz düzenleyin

  ```
   nano .env
   ```

Burada açılan pencerede <br><br>


INERY_ACCOUNT="HESAP ADINIZ" <br>
PRIVATE_KEY="KEYİNİZ"<br>
NODE_URL="http://NODEİPADRESİ:8888" 
<br><br>

ctrl +X  Yes diyip çıkıyoruz.


## 4) 8888 port açma 

RPC Örneği Çalıştır

```
sudo ufw allow 8888
```

<br>

## 5) Çalıştırma

```
npm run rpc-example
```
