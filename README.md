# open_nsfw_onnx_sample
NSFW画像検出モデル([open_nsfw_android](https://github.com/devzwy/open_nsfw_android))をColaboratory上で動かすサンプルです。<br>
ONNXに変換したモデルも同梱しています。<br>

# How to use
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kazuhito00/open_nsfw_onnx_sample/blob/master/open_nsfw_onnx_sample.ipynb)<br>
[Open In Colab]ボタンを押し、Colaboratoryでノートブックを開き、<br>
最初のセルから順に実行してください。<br><br>
試す画像を変更する際はimread_from_url()のURLを変更してください。<br>
```
from imread_from_url import imread_from_url

image = imread_from_url('https://raw.githubusercontent.com/Kazuhito00/AnimeGANv2-ONNX-Sample/main/sample.jpg')
```

# Reference
* [devzwy/open_nsfw_android](https://github.com/devzwy/open_nsfw_android)

# Author
高橋かずひと(https://twitter.com/KzhtTkhs)
 
# License 
open_nsfw_onnx_sample is under [Apache-2.0](LICENSE).

# License(Image)
女性の画像は[フリー素材ぱくたそ](https://www.pakutaso.com)様の写真を利用しています。
