## フォルダ構成

ex11/<br>
　 ├ Dockerfile <br>
　 ├ requirements.txt<br>
　 ├ python/<br>
　 │ 　 └ src/<br>
　 │ 　　　 └ sample1.py<br>
　 └ docker-compose.yml<br>

## コマンド

docker-compose up<br>
docker-compose.yml を元にイメージとコンテナを作成<br><br>
docker-compose up -d<br>
基本的にサービス(DB や python 等)はバックグラウンドで起動するのでこちらのコマンドを使う<br><br>
docker-compose down --rmi all<br>
イメージとコンテナを削除する
