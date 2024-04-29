# サンプルファイルを作成

# 開発中はRUNは重ねてビルド時のレイヤはキャッシュを使うようにする。
# 最終的には綺麗にまとめる

# COPYは単にコピーしたい時に使用
# ADDはtarなどの圧縮ファイルをコピーする時に使う（コピー時に自動で解凍される）

FROM ubuntu:latest
#RUN apt-get update && apt-get install -y \
#    curl \
#    nginx \
#    cvs
#RUN mkdir new_dir
#COPY something new_dir/
ADD compressed.tar /
CMD ["ls"]
