# Tell git to globally ignore .DS_Store 

https://gist.github.com/benbahrenburg/1129364

    git config --global core.excludesfile ~/.gitignore
    echo .DS_Store >> ~/.gitignore
