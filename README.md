## はじめに

`GAN-library` リポジトリは、Generative Art を作成するためのライブラリです。NFT アバターやコレクターズアイテムを作成する目的で開発されました。このライブラリは、[Scrappy Squirrels](https://www.scrappysquirrels.co/) プロジェクトのアートワークを生成するために使用されました。

## 特徴

### 60種類以下の特徴で100万枚以上の画像を生成可能
本ライブラリを使用することで、特徴量の組み合わせごとに画像を生成することができます。例えば、[Bored Apes](https://boredapeyachtclub.com/#/home) のようなプロジェクトで Generative Art を生成する場合、このライブラリは12億匹以上の異なる猿を生成することができます。

### レアリティの重みの追加
また、このライブラリでは、各特徴の希少性を完全にコントロールできるように、画像生成プロセスを設定することができます。

### NFT に準拠した JSON メタデータの生成
OpenSeaメタデータ要件（ひいては一般的なNFTメタデータ規格）に準拠した、NFTのJSONメタデータを生成する機能が追加されました。


### ファジーフレンドリー
このライブラリは、（Pythonなどの）プログラミングの知識がなくても使うことができます。

## インストール

**このリポジトリをクローンしてください**。

**Clone this repository**

```git clone https://github.com/rounakbanik/generative-art-nft.git```

**Install required packages**

```pip install Pillow pandas progressbar2```

Upload your input assets in the `assets` folder, fill up the `config.py` file, and then run `python nft.py`.

In order to generate JSON metadata, define BASE_NAME, BASE_IMAGE_URL, and BASE_JSON in `metadata.py` and then run `python metadata.py`.

## Usage

I have authored a detailed tutorial explaining how to use this library. Check it out [here](https://medium.com/scrappy-squirrels/tutorial-create-generative-nft-art-with-rarities-8ee6ce843133)

## About Scrappy Squirrels

<img src='squirrels.gif' height="250" width="250" />

This library was created as part of the Scrappy Squirrels Project.

Scrappy Squirrels is a collection of 10,000 randomly generated NFTs on the Ethereum Blockchain. Scrappy Squirrels are meant for buyers, creators, and developers who are completely new to the NFT ecosystem.

The community is built around learning about the NFT revolution, exploring its current use cases, discovering new applications, and finding members to collaborate on exciting projects with.
