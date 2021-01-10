# fictional-chainsaw

![fictionalChainsaw](https://pbs.twimg.com/media/ErC3ldvUcAEySUG?format=jpg&name=large)

## Usage

`git clone https://github.com/Ningensei848/fictional-chainsaw.git`
`docker-compose build && docker-compose up`

#### 要望

- プログラミングコンテストのために実行環境＋テスト環境がほしい
- ブラウザ上で機能してほしい
- 自作ライブラリも使えるようにしたい

#### 要求

- Jupyter lab を建てて，プロコン用の実行環境がほしい
  - 言語は python, rust, etc.
- test 環境も同時に整っていてほしい
  - pytest, etc.

#### 要件

- jupyter lab を docker 経由で建てる．

#### 仕様

- `FROM jupyter/minimal-notebook` のイメージをベースとする

### pie in the sky

- `python`, `rust`, `c++` がすべて自前のローカル環境で動いてほしい
- 加えて，各自テストと自作ライブラリが使えると嬉しい
  - これがあれば，Github pages とかで連携もできるはずなので
