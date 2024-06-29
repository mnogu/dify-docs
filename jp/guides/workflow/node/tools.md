# ツール

### 定義

ワークフロー内で豊富なツール選択が提供されており、ツールは三つのタイプに分かれています：

* **内蔵ツール**、Dify 第一方が提供するツール
* **カスタムツール**、OpenAPI/Swagger 標準フォーマットでインポートまたは設定されたツール
* **ワークフロー**、ツールとして公開されたワークフロー

内蔵ツールを使用する前に、ツールに **認可** を行う必要があるかもしれません。

内蔵ツールが使用要求を満たさない場合は、**Dify メニュー ナビゲーション --ツール** 内でカスタムツールを先に作成することができます。

また、より複雑なワークフローを編成し、それをツールとして公開することもできます。

<figure><img src="../../../.gitbook/assets/image (231).png" alt="" width="258"><figcaption><p>ツール選択</p></figcaption></figure>

<figure><img src="../../../.gitbook/assets/image (232).png" alt=""><figcaption><p>Google 検索ツールで外部知識を検索</p></figcaption></figure>

ツールノードの設定は一般的に二つのステップに分けられます：

1. ツールの認可/カスタムツールの作成/ワークフローをツールとして公開
2. ツール入力とパラメータの設定

カスタムツールの作成とツールの設定方法については[ツール設定説明](https://docs.dify.ai/v/zh-hans/guides/tools)を参照してください。