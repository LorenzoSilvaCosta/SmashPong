# SmashPong

Atualizações automáticas do jogo. O app (APK) consulta `ota/version.json` ao abrir; se houver código mais novo
com os mesmos dados pesados (`dataV`), baixa `ota/payload-<versionCode>.json` e passa a usá-lo.
Gerado por `jogo/montar.sh` do projeto; não editar à mão.
