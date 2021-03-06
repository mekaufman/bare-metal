---
copyright:
  years: 1994, 2017
lastupdated: "2017-06-27"
---

{:shortdesc: .shortdesc}
{:new_window: target="_blank"}

# CPU 速度がどうして正しくないのでしょうか?

サーバーにログインして CPU 情報を確認すると、プロセッサーの速度が正しくないことに気付くことがあります。この矛盾の原因は、Enhanced Intel SpeedStep Technology (EIST) の可能性があります。EIST は、動的周波数スケーリング・テクノロジーの Intel での名前です。このテクノロジーは、古いシステムでは、「*CPU スロットル*」や「*バス・スルーイング*」とも呼ばれます。一部の AMD システムでは、「*Cool'N'Quiet*」や「*PowerNow!*」と呼ばれる類似テクノロジーが搭載されています。これらのテクノロジーはすべて同じというわけではありませんが、目標は同じです。それは、プロセッサーの使用率が高くないときに CPU 速度を低下させることで、電力消費量および発熱を低下させることです。サーバーに再び負荷がかかるようになると、必要に応じてクロック速度を上げます。

ご使用のサーバーの Intel プロセッサーで SpeedStep がサポートされるかどうかを確認するには、カスタマー・ポータルで以下のようにします。 
1. **「デバイス」**をクリックします。
* リストでサーバーを識別します。
* サーバー名をクリックして、**「デバイスの詳細」**を表示します。
* **「ハードウェア」**というタイトルのサブセクションを見つけ、サーバーのプロセッサーの CPU 速度にあるモデル番号を確認します。
* サーバー・プロセッサーのモデル番号を控え、[Intel プロセッサー検索機能](http://processorfinder.intel.com/)にアクセスします。その番号を使用して、プロセッサーに関する詳細情報や、Enhanced Intel SpeedStep Technology がサポートされるかどうかを確認します。

EIST は、確立されたテクノロジーです。EIST をオフにする理由はないはずです。ただし、この機能を使用しないことにした場合は、サポート・チームに対してチケットをオープンし、この機能の無効化を依頼してください。この機能を無効にする際に、サーバーはリブートされます。
