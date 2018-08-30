---

copyright:
  years:  2018
lastupdated: "2018-05-15"

---

# 顧客管理プールについて

顧客管理プールは、常に組織で利用できるサーバーのセットにアクセスできるようにします。これらのサーバーは、仕様に合わせて構成されます。サーバーは、必要なときにプールから注文できます。

この機能は、組織が頻繁に、ピーク期間中に使用するための多くのサーバーをプロビジョンする必要がある場合に適しています。この機能を使用すると、最低限必要な数のサーバーのみを使用できますが、追加のニーズを満たすために常に多数のサーバー・セットを使用可能にしておくことができます。

## 使用例

会社 A は、日常業務に 1000 台のアクティブ・サーバーを使用しています。ただし、ピーク時には、500 台の追加サーバーが必要になる場合があります。追加のサーバーは、迅速に稼働状態にする必要があります。

ニーズを満たすために、会社 A は IBM に連絡して、サーバーの管理対象プールをセットアップします。プールのセットアップ後に、プール内のサーバーの数を 500 に設定する API 呼び出しを行います。

7 月には、会社 A はプールから 250 台の追加サーバーが必要になります。250 台のサーバーを注文します。この注文は、プールからの 250 台のサーバーで迅速に実行されます。注文が完了すると、常に 500 台が使用可能になるように、250 台のサーバーが会社 A の管理対象プールに追加されます。


## 次のステップ

組織が顧客管理プールを使用する必要がある場合は、[顧客管理プールのプロビジョン](../bare-metal/managedPool_provision.html)を参照してください。