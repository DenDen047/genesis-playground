# Genesis Playground

## Setup on macOS (M-series)

```bash
$ CONDA_SUBDIR=osx-arm64 conda create -n genesis python=3.12
$ conda activate genesis
$ conda env config vars set CONDA_SUBDIR=osx-arm64
$ conda deactivate
$ conda activate genesis
$ pip install genesis-world
$ pip install torch
```

## Usage

```sh
$ cd docker && docker compose up -d --build
$ docker compose down && docker compose up -d --build && docker exec -it [container_name] bash
```

```bash
$ python3.12 -m venv .venv
$ source .venv/bin/activate

## pip install ...

$ deactivate
```

## Reference

- [【Pythonの仮想環境を比較】〜オススメを紹介 〜](https://youtu.be/r4SkIhQThe0?si=kziY5m9s05gCk9Hx)
- [モダンなPyTorchのテンプレ](https://zenn.dev/dena/articles/6f04641801b387)
