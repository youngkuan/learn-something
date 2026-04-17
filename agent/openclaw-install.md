部署
./docker-setup.sh

http://127.0.0.1:18789/?token=你的token

docker exec -it be2afc80e425 openclaw config get gateway
加密了，不行
直接查看配置文件
cat ~/.openclaw/openclaw.json


令牌：1a7839e7e8bda92dc719c6bf3e2decfa55c214ea1a48562f17e051095aa818c1

问题记录：openclaw登录提示pairing required

docker exec -it be2afc80e425 openclaw devices list

docker exec -it be2afc80e425 openclaw devices approve 9f96bfb0-a59d-4ab6-85db-89931c414da4

谷歌专用密码：pogf efcb qfiy rkvn

升级openclaw
docker exec -it be2afc80e425 openclaw update