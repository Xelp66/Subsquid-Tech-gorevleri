# Subsquid Tech gorevleri
 14.12.2023 Subsquid tech gorevleri

 npm install --global @subsquid/cli@latest

 sqd --version

 # Buna benzer birsey cikmali
 @subsquid/cli/2.6.1 linux-x64 node-v20.5.1

 # Bu komutla Squid dosyasi olustur icine gir
 sqd init my-cryptopunks-squid -t https://github.com/subsquid-quests/cryptopunks-squid
 cd my-cryptopunks-squid

 # Squid dosyasinin icinde my-cryptopunks-squid dosyasi olustu. Gorevler kismindan Get Key tikla ve cryptopunks.key isimli dosyayi my-cryptopunks-squid/ query-gateway/keys alt klasorune yapistir

 sqd up

 npm ci
 sqd build
 sqd migration:apply

 sqd run .

 # loglar bu sekilde olmali
 [api] 23:33:48 WARN  sqd:graphql-server enabling dumb in-memory cache (size: 100mb, ttl: 1000ms, max-age: 1000ms)
 [api] 23:33:48 INFO  sqd:graphql-server listening on port 4350
 [processor] 23:33:49 INFO  sqd:processor processing blocks from 11000000
 [processor] 23:33:49 INFO  sqd:processor using archive data source
 [processor] 23:33:49 INFO  sqd:processor prometheus metrics are served at port 36935
 [processor] 23:33:52 INFO  sqd:processor 11005159 / 18377705, rate: 1756 blocks/sec, mapping: 352 blocks/sec, 311 items/sec, eta: 1h 10m
 [processor] 23:33:57 INFO  sqd:processor 11010199 / 18377705, rate: 1735 blocks/sec, mapping: 488 blocks/sec, 428 items/sec, eta: 1h 11m

 # gorev puani aldiktan sonra

 sqd down