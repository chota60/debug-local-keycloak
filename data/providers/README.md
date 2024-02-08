# what is this?
追加したい SPI があればこのディレクトリに格納して、docker-compose で mount させましょう

## 例：keycloak-discord
https://github.com/wadahiro/keycloak-discord

を使いたい場合、
- `keycloak-discord-0.5.0.jar` を配置
- `volumes` に `- ./data/providers/keycloak-discord-0.5.0.jar:/opt/keycloak/providers/keycloak-discord-0.5.0.jar`  を追記
