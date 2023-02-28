Openpose Editorの仕様

# カメラ制御（OrbitControls）

PC
- ジョイント以外がカメラ制御になる
- 右ドラッグ操作で回転
- Shift + ドラッグ操作で移動
- スクロール操作でズーム

スマホ
- 1touchは回転
- 2touchはズーム

# 人間の操作

全般
- IKはON/OFF可能

2Dモード
- 3Dモデルを2Dで操作する、IKは2D-IKになる
- Z軸は基本的に0
- 今までのように伸びたりはしない（3Dモデルだから）
- ジョイントをドラッグ操作する

3Dモード
- カメラ制御を用いながら3Dで編集する
- ジョイントをドラッグ操作する

あとgithubに異型、奇形に関するissueがいくつかあるんだけどどう対応しようか :scream: