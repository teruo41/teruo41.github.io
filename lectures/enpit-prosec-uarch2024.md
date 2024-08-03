---
layout: normal
title: enPiT-Pro Security マイクロアーキテクチャ攻撃 (2024)
---

<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>

# {{ page.title }}

## 概要

- 開講時期：2024年8月3日
- 教　　室： 西新プラザ多目的室（Zoom会議とハイブリッド）  
  接続先は別途連絡があります。

## 講義予定

|時間|内容|
|:--:|:---|
|10:00 - 12:00|導入、CPUを対象としたマイクロアーキテクチャ攻撃に関する講義、演習（準備編）|
|13:00 - 16:20|メモリを対象とした攻撃に関する講義、演習（再現編）|

## 講義資料

||講義資料１|演習|
|:-:|:-:|:-:|
|導入|[導入資料]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-intro-v01.pdf)||
|午前|[マイクロアーキテクチャ攻撃１]({{ site.url }}/contents/enpit-prosec-uarch2024/MA-1-v01.pdf)|[演習１]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-ex-1-v01.pdf)|
|午後|[マイクロアーキテクチャ攻撃２]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-2-v01.pdf)|[演習２]({{ site.url }}/contents/enpit-prosec-uarch2022/MA-ex-2-v01.pdf)|

## 講義のための準備について
この講義では、演習時に Docker コンテナを使います。  
お手元の環境で Docker コンテナを実行してください。  
[https://docs.docker.com/get-docker/](https://docs.docker.com/get-docker/)

可能な方は、講義までに[演習１（準備編）]({{ site.url }}/contents/enpit-prosec-uarch2024/MA-ex-1-v01.pdf)まで実施を済ませておいてください。  
Docker for Windows をお使いの場合、資料中の docker コマンドの前の sudo は不要です。  
2 GB 程度のファイルをダウンロードする必要があります。  

資料の文字列をコピー＆ペーストするとうまくいかない場合があります。  
過去に AWS の T2 インスタンスで演習に挑戦した方で計算が終わらなかったケースがありました。

### Docker をインストールできない場合

Virtualbox など仮想環境を作ることができるツールを使って、Docker を実行できるようにしてください。

## レポートに関して
レポート提出は任意とします。  
理解度を確認したいという方は取り組んでください。

資料を読んで取り組める方は講義を待たずにレポート課題に取り組み始めていただいても構いません。  

フォーマットは任意とします。  
記名を忘れずにしていただくのと、どの設問に答えているのかわかるように構成していただくようお願いします。

提出は以下のようにしてください。
- 提出先：tteruo _[at]_ kyudai.jp
- 件　名：「SECKUNマイクロアーキテクチャ攻撃レポート（氏名）」
- 期　限：2024/10/1

