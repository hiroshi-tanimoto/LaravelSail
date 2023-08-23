<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>



## ローカルでの環境準備（Windows）
参考にしたサイト：https://qiita.com/monji586/items/49276a84e1396cc77086

- WSL2を使えるようにする
- Ubuntuインストール
- Docker Desktopをインストール
- Laravel ＋ Laravel Sail インストール　``` curl -s https://laravel.build/docker-laravelsail-dev | bash  ```
- コンテナの作成・起動　``` cd docker-laravelsail-dev && ./vendor/bin/sail up -d ```
- http://localhost/ で画面を確認

![image](https://github.com/hiroshi-tanimoto/LaravelSail/assets/50011696/cacd6e51-5086-4f22-a7a5-543727feb586)
