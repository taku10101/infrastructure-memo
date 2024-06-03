## 統合版サーバー　

### 環境

ubuntu

bedrock Server
https://www.minecraft.net/ja-jp/download/server/bedrock

## やったこと

### udp port 解放

v4 >> 19132
v6 >>19132

### 起動コマンド

```bash
 LD_LIBRARY_PATH=. ./bedrock_server
```

###　詳細設定
ファイル
server.properties

メモリ割り当て明記はできなさそう
