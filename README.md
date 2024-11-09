# molstar_test
[molviewspec](https://molstar.org/mol-view-spec/)の使い方についての勉強用リポジトリ

## URLでmvsjを読み込めるようにする方法
以下の形式で、molstarにmvsjのraw fileを渡せばよい
```
https://molstar.org/viewer/?mvs-format=mvsj&mvs-url=[raw fileへのリンク]

# 例
https://molstar.org/viewer/?mvs-format=mvsj&mvs-url=https://raw.githubusercontent.com/Sakura-Book/molstar_test/main/1stm.mvsj
```

## 内容
- [generate_mvsj.ipynb](./generate_mvsj.ipynb)
  - [molviewspecのデモ用ノートブック](https://colab.research.google.com/drive/1O2TldXlS01s-YgkD9gy87vWsfCBTYuz9)を参考に、mvsjファイルを作るためのノートブック

- [viperdb_test.ipynb](./viperdb_test.ipynb)
  - viperdbからWebAPI経由でカプシドのPDBIDを取得するためのノートブック

- [1cbs.mvsj](./1cbs.mvsj)
  - 動作確認のため、[molstar](https://github.com/molstar/molstar/blob/master/examples/mvs/1cbs.mvsj)よりコピーしたもの
  - [1cbs.mvsj](https://molstar.org/viewer/?mvs-format=mvsj&mvs-url=https://raw.githubusercontent.com/Sakura-Book/molstar_test/main/1cbs.mvsj)

- [1stm.mvsj](./1stm.mvsj)
  - [molviewspecのデモ用ノートブック](https://colab.research.google.com/drive/1O2TldXlS01s-YgkD9gy87vWsfCBTYuz9)で作成したファイル
  - [1stm.mvsjをmolstarで見る](https://molstar.org/viewer/?mvs-format=mvsj&mvs-url=https://raw.githubusercontent.com/Sakura-Book/molstar_test/main/1stm.mvsj)

- [mol-star_state_2024-11-6-18-43-37.molj](./mol-star_state_2024-11-6-18-43-37.molj)
  - moljファイルを指定したURLをmolstarで読み込めるかどうかテストするために作成したもの。以下の通り、フォーマットエラーで読み込むことはできなかった。
  - [moljファイルをmolstarで見る](https://molstar.org/viewer/?mvs-format=mvsj&mvs-url=https://raw.githubusercontent.com/Sakura-Book/molstar_test/main/mol-star_state_2024-11-6-18-43-37.molj)