---
layout: normal
title: enPiT-Pro Security マイクロアーキテクチャ攻撃 (2022)
---

<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>

# enPiT-Pro Security マイクロアーキテクチャ攻撃

## 概要

- 開講時期：2022年10月15日
- 教　　室：オンライン（Zoom会議）  
  接続先は別途連絡があります。

## 講義予定

|時間|内容|
|:--:|:---|
| 9:00 - 12:00|導入、CPUを対象としたマイクロアーキテクチャ攻撃に関する講義、演習（準備編）|
|13:00 - 16:00|メモリを対象とした攻撃に関する講義、演習（再現編）|

## 講義資料

||講義資料１|演習|
|:-:|:-:|:-:|
|導入|[講義資料]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-intro-v01.pdf)||
|午前|[マイクロアーキテクチャ攻撃１]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-1-v01.pdf)|[演習１]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-ex-1-v01.pdf)|
|午後|[マイクロアーキテクチャ攻撃２]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-2-v01.pdf)|[演習２]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-ex-2-v01.pdf)|

## 講義のための準備について
この講義では、演習時に Docker コンテナを使います。
お手元の環境で Docker コンテナを実行してください。
https://docs.docker.com/get-docker/

可能な限り、講義までに演習１（準備編）まで実施を済ませておいてください。
うまくいかない場合や、不明な点がある場合は、Slack の #20221015-tanimoto で連絡してください。

仮想環境として VirtualBox を利用している方向けに Docker コンテナを実行可能なイメージを配布します。
VirtualBox を使わなくても手元で Docker を実行できる場合は、この環境を使わなくても構いません。
（Docker for Windows をお使いの場合、資料中の docker コマンドの前の sudo は不要です。）

### イメージ配布 URL
- http://www8281uo.sakura.ne.jp/enpit-prosec-ua.zip
- 九大のOffice365にログイン可能な方は以下からも同じファイルをダウンロードできます。  
  https://qu365-my.sharepoint.com/:u:/g/personal/tanimoto_teruo_547_m_kyushu-u_ac_jp/ETTl7jqqmWdLjofzgXMa6IMBlnNrXUi5gENQwhzQ9SW3uQ?e=dYn91N

### zip ファイルの md5sum
1312c3b3ebfca24f38acb69fefc510cd

### 仮想マシンのユーザ情報
- ユーザ名： uauser
- パスワード： prosec-ua  
  （rootパスワード： enpit-prosec-ua）

### Docker コンテナ実行可否の確認方法
zip ファイルを解凍し、中の input-prosec-ua.vbox を開いてください。

仮想マシンが起動したら、 uauser でログインし、以下のコマンドを実行してください。
sudo docker run hello-world

This message shows that your installation appears to be working correctly
のような文字列が出力されれば正しく Docker を実行できています。

### VirtualBox 使用時の注意点
当日の演習では、VirtualBox の画面よりも大きなターミナルが必要になると思いますので、SSH などを使ってこの仮想マシンに端末エミュレータから接続できるようにしておくのをおすすめします。

よろしくお願いします。
