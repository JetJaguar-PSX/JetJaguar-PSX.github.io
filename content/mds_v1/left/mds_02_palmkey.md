---
title: "無限打鍵山脈 v1 2合目：手のひらキーの組み立て（左手用）"
date: 2025-04-11T00:25:45+09:00
description : ""
tags: [""]
image : ""
draft: false
---

自作キーボードキット「無限打鍵山脈」のビルドガイド2合目、手のひらで押すキーの組み立てです。

&nbsp;
&nbsp;

## 目次
- [使用する部品](#section1)
- [フレームの組み立て](#section2)
- [基板4-2にはんだ付け](#section3)
- [接続用基板4-2にはんだ付け](#section4)
- [基板の取り付け](#section5)
- [2合目、踏破！！](#section6)

&nbsp;
&nbsp;

<h2><a id="section1">使用する部品</a></h2>

### キットに含まれるもの

|  品目  |  必要数  |
| ---- | ---- |
|  アクリル製パーツ  |  4種類各1  |
|  基板4-2（1キー）  |  1  |
|  接続用基板4-2（2ピン）  |  1  |
|  ダイオード  |  1  |
|  垂直取付用スペーサー  |  10個  |
|  3mmネジ  |  7個  |
|  4mmネジ  |  20個  |
|  L型ピンヘッダ（1x2ピン）  |  2  |
|  ピンソケット（1x2ピン）  |  2  |

&nbsp;

### キット以外で必要なもの

|  品目  |  必要数  |
| ---- | ---- |
|  スイッチソケット  |  1個  |

&nbsp;
&nbsp;

<h2><a id="section2">フレームの組み立て</a></h2>

### 奥側のフレームの組み立て

![](/images/mds_v1/left/02/frame/frame_E_panels.jpg)

この2つのパネルを使います。

![](/images/mds_v1/left/02/frame/frame_E-1.jpg)

画像のように、片方のパネルに垂直取付用スペーサーを**4mm**ネジで取り付けます。

![](/images/mds_v1/left/02/frame/frame_E-2.jpg)

もう一方のパネルを**4mm**ネジで止めます。

![](/images/mds_v1/left/02/frame/frame_E_set.jpg)

組み立てたフレームをメイン基板に**3mm**ネジで止めます。

&nbsp;

### 手前側のフレームの組み立て

![](/images/mds_v1/left/02/frame/frame_F_panels.jpg)

この2つのパネルを使います。

![](/images/mds_v1/left/02/frame/frame_F-1.jpg)

画像のように、片方のパネルに垂直取付用スペーサーを**4mm**ネジで取り付けます。

![](/images/mds_v1/left/02/frame/frame_F-2.jpg)

もう一方のパネルを**4mm**ネジで止めます。

![](/images/mds_v1/left/02/frame/frame_F_set.jpg)

組み立てたフレームをメイン基板に**3mm**ネジで止めます。

&nbsp;
&nbsp;

<h2><a id="section3">基板4-2にはんだ付け</a></h2>

![](/images/mds_v1/left/02/key/palmkey_parts.jpg)

画像の基板にダイオードとスイッチソケットをはんだ付けします。

**基板の裏表をよくご確認ください。**

![](/images/mds_v1/left/02/key/palmkey_diode.jpg)

基板の**表面**からダイオードを差し込みます。

![](/images/Diode.png)

ダイオードには向きがあり、間違えるとキーが動作しなくなるなどの不具合を生じます。向きは上図の通りです。

基板の**裏面**にてダイオードにはんだ付けします。はみ出たダイオードの足はニッパーやペンチなどで切り落としてください。

![](/images/mds_v1/left/02/key/palmkey_socket.jpg)

基板の**裏面**にスイッチソケットをはんだ付けします。

&nbsp;
&nbsp;

<h2><a id="section4">接続用基板4-2にはんだ付け</a></h2>

![](/images/mds_v1/left/02/connector/palmkey_connector_parts.jpg)

L型ピンヘッダとピンソケットを用います。

![](/images/mds_v1/left/02/connector/palmkey_pin.jpg)

画像のようにL型ピンヘッダとピンソケットを繋げます。

![](/images/mds_v1/left/02/connector/palmkey_connector_pinset.jpg)

L型ピンヘッダを接続用基板に差し込み、はんだ付けします。このとき、ピンヘッダの向きが傾かないようにご注意ください。

&nbsp;
&nbsp;


<h2><a id="section5">基板の取り付け</a></h2>

![](/images/mds_v1/left/02/connector/palmkey_connector_set.jpg)

画像のように、メイン基板にピンソケットの先端が刺さるように接続用基板4-2をあてがいます。安定しない場合はマスキングテープで仮止めしてください。

![](/images/mds_v1/left/02/connector/palmkey_set.jpg)

メイン基板とは反対側のピンソケットが刺さるように、基板4-2を置き、**3mm**ネジでフレームに止めます。

![](/images/mds_v1/left/02/connector/palmkey_connector_solder1.jpg)
![](/images/mds_v1/left/02/connector/palmkey_connector_solder2.jpg)

ピンソケットをはんだ付けします。

&nbsp;
&nbsp;

<h2><a id="section6">2合目、踏破！!</a></h2>

これにて手のひらキーの組み立ては完了です。続いては親指キーとジョイスティックの組み立てです。

[3合目：親指キーとジョイスティックの組み立て（左手用）](./../../mds_v1/left/mds_03_row4)