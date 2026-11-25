# 電圧降下計算機の使い方



線径規格、断面積、抵抗から直流・単相・平衡三相回路の電圧降下を推定します。





## 使い方



1. モデルを選びます。三相では線間電圧と線電流を入力します。距離は片道です。
2. 距離上限は入力した降下率で計算します。許容電流、温度、施工要件は別途確認してください。







## 例



### 入力



```
120 V、単相、500 ft、1 A、1.2 Ω/km
```



### 期待される結果



```
降下 0.37 V、0.30%
```





<a id="case-study"></a>



## ケーブル表を使う



1. 係数1 mV/(A·m)、片道50 m、100 Aでこの区間の降下は5 Vです。Schneider の例では上流の10 Vを加え、経路全体で15 Vです。



[入力例を実行](<https://toolpony.com/ja/tools/voltage-drop-calculator/#example-cable-table>)





## 三相並列配線



各相2本で20 Aを分担します。400 V、100 m、R = 1 Ω/km、X = 0.5 Ω/km、遅れ力率0.8で電圧降下1.91 V、負荷端398.09 Vです。



[入力例を実行](<https://toolpony.com/ja/tools/voltage-drop-calculator/#example-parallel-cable>)







## 電源を超える降下



24 V直流、10 A、片道1 km、5 Ω/kmでは往復の電圧降下は100 Vです。この電流での負荷電圧は推定できません。



[入力例を実行](<https://toolpony.com/ja/tools/voltage-drop-calculator/#example-cable-limit>)







## 試してみる

[ツール全体を開く · 電圧降下計算機](<https://toolpony.com/ja/tools/voltage-drop-calculator/>)





## 計算方法



片道長さと同一仕様の並列導体数を使います。直流・単相では I·L·R に 2、平衡三相では √3 を掛けます。遅れ負荷では力率から R と X の寄与を求めます。線径での推定は約 20 °C の公称値です。実際のケーブルはメーカー値を入力してください。



$$
\Delta V=\frac{k I L R_{\rm eff}}{n},\quad k=2\ \text{(DC, 1)}\phi,\quad k=\sqrt{3}\ \text{(3)}\phi
$$



$$
R_{\rm eff}=R\cos\theta+X\sin\theta,\quad \%\Delta V=100\frac{\Delta V}{V_s}
$$







## 計算モード





### 既知の抵抗・インピーダンス



- 資料の値 · 導体インピーダンス / 回路の電圧降下係数
- 単位長さあたりの抵抗・インピーダンス
- 長さあたりの単位 · Ω/km / Ω/m / mΩ/m / Ω/1000フィート / Ω/ft / mΩ/ft
- 表の回路係数 · mV/(A·m)
- 電圧 · V
- 回路 · DC / 単相交流 / 三相交流
- 相あたりの並列導体数
- 片道距離
- 長さの単位 · フィート / m / mi / km
- 電流 · A
- 距離推定の電圧降下上限 · %







### 線径規格で推定



- 材質 · 銅 / アルミニウム / 銀 / 金
- 線径規格
- 電圧 · V
- 回路 · DC / 単相交流 / 三相交流
- 相あたりの並列導体数
- 片道距離
- 長さの単位 · フィート / m / mi / km
- 電流 · A
- 距離推定の電圧降下上限 · %







### 断面積で推定



- 材質 · 銅 / アルミニウム / 銀 / 金
- 断面積 · mm²
- 電圧 · V
- 回路 · DC / 単相交流 / 三相交流
- 相あたりの並列導体数
- 片道距離
- 長さの単位 · フィート / m / mi / km
- 電流 · A
- 距離推定の電圧降下上限 · %







### 抵抗とリアクタンス



- 抵抗
- 単位長さあたりのリアクタンス
- 長さあたりの単位 · Ω/km / Ω/m / mΩ/m / Ω/1000フィート / Ω/ft / mΩ/ft
- 遅れ力率
- 電圧 · V
- 回路 · DC / 単相交流 / 三相交流
- 相あたりの並列導体数
- 片道距離
- 長さの単位 · フィート / m / mi / km
- 電流 · A
- 距離推定の電圧降下上限 · %







**計算・処理の参考資料** [Schneider Electric · Voltage drop in steady load conditions](<https://www.electrical-installation.org/enwiki/Calculation_of_voltage_drop_in_steady_load_conditions>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Fvoltage-drop-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/voltage-drop-calculator/)
