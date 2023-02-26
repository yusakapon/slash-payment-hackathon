# Back Slash

Back Slashはリファラルプログラムを実現するSlash Extensionです。  

`紹介者のWalletAddress`、`報酬率`、`キャッシュバック率`を設定することで、紹介者への報酬の支払いと紹介で購入者した人へのキャッシュバックが実現できます。

## テストサイト
https://back-slash.vercel.app/

テストサイトでは以下の設定をしています。


| リファラルコード | 報酬振り込みwallet | 報酬率 | 購入者へのキャッシュバック率 | 
| ------------- | ------------- | ------------- | ------------- | 
| なし  | - | -  | -  |
| test1 | `0xdfe3DDBcB66cbC3a88816C0f876F76b2B60884fe` | 1% | 2% |
| test2 | `0xDeBeA7Bf019285Cd3ddAd69A6aC1c6E5260d1083` | 3% | 0% |
| test3 | - | 0% | 5% |

## コントラクト

| ネットワーク | コントラクトアドレス | エクスプローラー | 
| ------------- | ------------- | ------------- | 
| Astar  | `0x2233AE1e9835636843cc445cA2817c732874AaF3` | [Link](https://blockscout.com/astar/address/0x2233AE1e9835636843cc445cA2817c732874AaF3)  | 
