# jupyter-book

## initialize

- `git clone git@github.com:dongorae/jupyter-book-initialize.git`
- 폴더명 변경 및 이동
- `rm -rf .git`
- `git init`
- ~~`pip install -r requirements.txt`~~

## setting
- logo.png
- favicon.png (변환 : <https://favicon.io/favicon-converter/>)
- intro.md
- _config.yml
- 섹션 폴더 생성
- 

## build & publish
- build : `jupyter-book build . --all`
- publish : `ghp-import -n -p -f _build/html`

