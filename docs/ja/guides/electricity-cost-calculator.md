# 電気料金計算機の使い方



消費電力、冷房能力と効率、または2回の検針値から電気料金を求め、日ごと・請求期間ごとの使用量を確認します。





## 使い方



1. 機器の消費電力、使用時間、単価を入力します。プリセットの例は変更できます。







## 例



### 入力



```
1,000 W、1 日 2 h、30 日、0.2/kWh
```



### 期待される結果



```
60 kWh、料金 12
```





<a id="case-study"></a>



## 窓用エアコンの消費電力を読む



1. LG LW6014ERの仕様は冷房能力6,000 BTU/h、消費電力530 Wです。1台を全負荷で1日8時間、30日間運転すると0.53 × 8 × 30 = 127.2 kWh。単価0.20なら使用量分の料金は25.44です。



[入力例を実行](<https://toolpony.com/ja/tools/electricity-cost-calculator/#example-window-power>)





## 2回の検針値で料金を確認



30日で検針値が612345.125から612492.365 kWhになりました。差は147.24 kWh、1日平均は4.908 kWhです。単価0.15なら使用量分は22.086で、基本料と税は別計算です。



[入力例を実行](<https://toolpony.com/ja/tools/electricity-cost-calculator/#example-meter-readings>)







## EERから消費電力を推定



冷房能力6,000 BTU/h、定格EERが12 BTU/Whなら消費電力は6,000 ÷ 12 = 500 Wです。全負荷で1日8時間、30日間の電力量は120 kWh。同じ運転条件の定格EERを使います。



[入力例を実行](<https://toolpony.com/ja/tools/electricity-cost-calculator/#example-cooling-eer>)







## 試してみる

[ツール全体を開く · 電気料金計算機](<https://toolpony.com/ja/tools/electricity-cost-calculator/>)





## 計算方法



使用量分の料金 = kWh × 単価。検針量は終了値と開始値の差です。冷房能力（BTU/h）をEERで、または冷房能力（W）をCOPで割ると消費電力が求まります。期間換算は月30.44日、年365.25日です。



$$
E_{\rm kWh}=M_1-M_0,\qquad P_{\rm W}=\frac{Q_{\rm Btu/h}}{\mathrm{EER}}=\frac{Q_{\rm W}}{\mathrm{COP}}
$$



$$
E_{\rm kWh}=P_{\rm kW}\,t_{\rm h}\,f\,n,\qquad C=E_{\rm kWh}\,r
$$







## 計算モード





### 日数を指定



- 計算基準 · 消費電力 / 冷房能力 / メーター指示値
- 消費電力
- 電力の単位 · W / kW / BTU/h / PS / TR
- 冷房能力
- 冷房能力の単位 · BTU/h / kW / TR
- 効率の種類 · EER (BTU/Wh) / COP (W/W)
- 定格効率
- 開始指示値 · kWh
- 終了指示値 · kWh
- 平均負荷 · %
- 台数
- 1 日の運転時間 · h
- 日数
- kWh あたりの料金







### 日・週・月・年の見積もり



- 家電のプリセット
- 計算基準 · 消費電力 / 冷房能力
- 消費電力
- 電力の単位 · W / kW / BTU/h / PS / TR
- 冷房能力
- 冷房能力の単位 · BTU/h / kW / TR
- 効率の種類 · EER (BTU/Wh) / COP (W/W)
- 定格効率
- 平均負荷 · %
- 台数
- 使用時間
- 使用時間の単位 · 分/日 / 1 日の運転時間 / 時間/週 / 時間/月 / 日/週 / 日/月 / 日/年 / 月/年
- kWh あたりの料金







**計算・処理の参考資料** [LG · LW6014ER electrical specification](<https://images.thdstatic.com/catalog/pdfImages/e3/e3b8396a-44d1-4372-b120-7532036b2488.pdf>) · [Ohio Consumers’ Counsel · Read an electric meter](<https://www.occ.ohio.gov/sites/default/files/2021-07/OCC-How-to-Read-an-Electric-Meter.pdf>) · [U.S. Department of Energy · Room air conditioner ratings](<https://www.energy.gov/sites/prod/files/2015/06/f22/room_ac_rfi.pdf>) · [NIST · International Table Btu](<https://www.nist.gov/pml/special-publication-811/nist-guide-si-footnotes>)



[ZooChief](<https://docs.toolpony.com/ja/about/>) · [結果の問題を報告](<https://github.com/ZooChief/ToolPony-Docs/issues/new?template=01-problem.yml&page=%2Fja%2Fguides%2Felectricity-cost-calculator%2F>)

[ドキュメント](https://docs.toolpony.com/ja/guides/electricity-cost-calculator/)
