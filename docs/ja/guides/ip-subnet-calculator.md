# IP サブネット計算機の使い方



IPv4およびIPv6ネットワーク、マスク、範囲、アドレス数を検査するか、またはIPがCIDRブロックに属しているかどうかをテストしてください。





## 例



### 入力



```
192.0.2.129 /27
```



### 期待される結果



```
ネットワーク 192.0.2.128/27、使用可能なホスト30件
```





<a id="case-study"></a>



## サブネット境界を確認



1. 192.0.2.128/27 の終端 .159 は範囲内のIPv4ブロードキャストです。.160 は範囲外で、IPv6 は別のアドレスファミリです。



[入力例を実行](<https://toolpony.com/ja/tools/ip-subnet-calculator/#example-subnet-boundary>)





## IPv6の両端



2001:db8::8/127 は ::8 と ::9 を含みます。順序は1、2で、IPv6にはブロードキャストがありません。



[入力例を実行](<https://toolpony.com/ja/tools/ip-subnet-calculator/#example-ipv6-endpoints>)







## 試してみる

[ツール全体を開く · IP サブネット計算機](<https://toolpony.com/ja/tools/ip-subnet-calculator/>)





## 計算方法



アドレスとプレフィックスマスクのビット単位 AND を取り、先頭のアドレスを求めます。ホスト部の組み合わせは 2^(アドレスのビット数 − プレフィックス長) 通りです。IPv4 の /31 は通常のホスト数の数え方を初期設定とし、RFC 3021 のポイントツーポイント方式も選べます。アドレスと同時に指定した CIDR プレフィックスが優先されます。



$$
\text{Addresses}=2^{w-p},\qquad w\in\{32,128\}
$$



IPv4は、プレフィックス長または連続した点線マスクを受け入れます。 たとえば、192.0.2.129 と 255.255.255.224 は、192.0.2.129/27 と同じネットワークを提供します。



プレフィックスサイズのカテゴリは、比較ツールのA/B/C規約に従います。 歴史的アドレスクラスは別々に表示されます。 CIDR会員の住所範囲を使用してください。 オプションのポイントツーポイント設定は、ホストカウントのみを /31 に変更します。







## 計算モード





### IPv4



- IPv4アドレスまたはCIDR
- プリフィックスまたはサブネットマスク
- 31ポイントツーポイントリンクで両方のアドレスを使用してください







### IPv6



- IPv6アドレスまたはCIDR
- プレフィックス







### 住所の会員登録を確認してください



- CIDRネットワーク
- 確認する住所







**計算・処理の参考資料** [IETF · RFC 4632 (CIDR)](<https://www.rfc-editor.org/rfc/rfc4632>) · [IETF · RFC 3021 (/31 links)](<https://www.rfc-editor.org/rfc/rfc3021>) · [IETF · RFC 5952 (IPv6 text)](<https://www.rfc-editor.org/rfc/rfc5952>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fip-subnet-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/ip-subnet-calculator/)
