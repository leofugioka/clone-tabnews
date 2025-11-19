# clone-tabnews

Implementação do tabnews para o curso.dev feito junto das aulas

# Criar Configuração do Editor

Para padronizar a formatação dos códigos javascript, utilizamos o "EditorConfig"

1 - Instalar extensão EditorConfig
2 - Criar arquivo `.editorconfig` e adicionar ao arquivo:

'''
root = true

[*{.js,jsx,ts,tsx}]
indent_style = space
indent_size = 2
'''

# Instalar prettier

`npm i prettier -D`

ou

`npm i prettier --save-dev`

Também: Instalar extensão Prettier do vscode

## Para prettier@3.0+

Criar `.prettierignore` e adicionat a pasta ".next/" ao arquivo

# Comando Docker para iniciar o banco de dados

`docker compose -f infra/compose.yaml up -d`

# Comando Docker para encerrar o banco de dados

`docker compose -f infra/compose.yaml down`
