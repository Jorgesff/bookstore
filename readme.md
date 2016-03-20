# BookStore

## Guia para a instalação e início do projeto

### Baixe e instale o projeto

Crie o diretório do projeto e entre
```
    mkdir bookstore
    cd boostore
```

Inicialize, baixe e instale o projeto
```
    git init
    git remote add origin https://github.com/Jorgesff/bookstore.git
    git pull origin master
```

Instale o node.js
```
    sudo apt-get update
    sudo apt-get install build-essential libssl-dev
    curl https://raw.githubusercontent.com/creationix/nvm/v0.16.1/install.sh | sh
    source ~/.bashrc
    nvm install 5.6.0
    nvm alias default 5.6.0
```

Vá para o diretório 'js' e instale as dependências do projeto
```
    cd js
    npm install
```

Rode o servidor e divirta-se
```
    cd ../
    node server.js
```
