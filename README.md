# AzureML-NLP

本リポジトリでは、Azure Machine Learning を利用した日本語の自然言語処理 NLP モデル構築のサンプルコードを提供します。Microsoft の [NLP Best Practice](https://github.com/microsoft/nlp-recipes) を参考にしています。

## コンテンツ
<style>
table td span {
	white-space: nowrap;
}
</style>

|   シナリオ    |  モデル |  概要 |  対応言語  |
|:-------------|:--------|:-------|:-----------|
|テキスト分類   |  BERT  | テキスト分類は、テキストのカテゴリーを学習し、予測する教師付き学習の 1 つです。 |Japanese|

## Get started

最初は [Azure Cognitive Service](https://azure.microsoft.com/ja-jp/services/cognitive-services/) の利用検討を推奨します。この学習済みのモデルで対応できない場合は、カスタムで機械学習モデルを構築する必要がございます。まず、[Setup](Setup.md) を参照し、必要なライブラリを導入してください。