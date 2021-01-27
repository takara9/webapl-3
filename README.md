# webapl-3 Rails on Ruby のコンテナ


docker build -t maho/webapl3:0.1 .
docker run -it -p 3000:3000 --name test --rm maho/webapl3:0.1 

curl http://localhost:3000

docker push maho/webapl3:0.1






## 参考資料
* DockerでRuby on Railsの環境構築を行うためのステップ【Rails 6対応】, https://qiita.com/kodai_0122/items/795438d738386c2c1966
* Dockerizing a Ruby on Rails Application, https://semaphoreci.com/community/tutorials/dockerizing-a-ruby-on-rails-application