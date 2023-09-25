# techdojo-liberty-sample
TechDojo向け WAS Liberty動作確認用サンプルになります。
Libertyのディレクトリー構成やファイルの確認、簡単なサンプルファイルのデプロイのお試しにどうぞ

# ビルド＆起動
```
docker-compose build
```
```
docker-compose up -d
```

# 動作確認
http://localhost:9080/sample
にアクセスして以下画面が表示されたらOK
![image](https://github.com/IBMDeveloperTokyo/techdojo-liberty-sample/assets/99166088/c655fc8b-0b34-4afc-a087-9c4baa06d465)

# 補足
上記Webアプリは以下フォルダにwarファイルをデプロイして動作させています。<br>
web/app/sample.war

※sample.warは以下サイトから入手<br>
https://tomcat.apache.org/tomcat-7.0-doc/appdev/sample/

