# ga_shift

## 目的
+ 各人のシフトの均等性を担保する
+ 各人のシフトの希望を可能な限り尊重する

## オペレーション
### パターン１：月ごとに作成する
+ ３ヶ月分ごとに帳尻合わせる
+ 毎月各人の事情をある程度反映可能
+ 各人に均等にシフトを配分できるか微妙

### パターン２：一気に１年分を作成
+ 各人に均等にシフトは配分可能
+ 各人の事情を反映できるか・・・

＝＞融合
+ **まず一気に１年分を作成してみる**
+ **各人の各月のシフト数を簡単に推定しておく _(均等性を担保）_**
+ **推定シフト数と各人の希望を考慮して月ごとに作成 _(各人の希望を尊重)_**
+ **一般科は最後に調整する**

### todo
+ 前年度の情報を収集
  + golden week
  + 年末年始
  + 三連休
  + 
+ 前年度の情報とシフトパターンから各人の各シフトパターンのtotal数を推定
+ total数から逆算して各人の各月のシフト数を推算

### 仕様
+ 16人
+ シフトのパターンを分類する
  + A 平日で、かつ、次の日が休日でない、かつ、2日後も休日でない（月〜水）
  + B 平日で、かつ、次の日が休日でない、かつ、2日後も休日である（木）
  + C 平日で、かつ、次の日が休日である（金）
  + D 土曜日
  + E 日・祝日
  + F 一般科

