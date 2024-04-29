# サンプルファイルを作成

# 開発中はRUNは重ねてビルド時のレイヤはキャッシュを使うようにする。
# 最終的には綺麗にまとめる

# COPYは単にコピーしたい時に使用
# ADDはtarなどの圧縮ファイルをコピーする時に使う（コピー時に自動で解凍される）

FROM ubuntu:latest
RUN mkdir sample_folder
WORKDIR /sample_folder
RUN touch testok