
# Automatização de Certificados

Este projeto consiste em um script Python que automatiza a criação de certificados assinados a partir de uma planilha de dados dos participantes de cursos.

## Funcionalidades

- Carrega os dados dos participantes a partir de uma planilha Excel.
- Gera certificados personalizados com base nos dados fornecidos.
- Utiliza imagens de certificado padrão e preenche com as informações dos participantes.

## Pré-requisitos

- Python 3.x
- Bibliotecas Python: `openpyxl`, `PIL`

## Instalação

1. Clone este repositório:

```


git clone https://github.com/seu-usuario/seu-repositorio.git


```

2. Instale as dependências:

```


pip install openpyxl Pillow


```

## Uso

1. Coloque a planilha de dados dos participantes no mesmo diretório do script Python, com o nome `planilha_alunos.xlsx`.
2. Execute o script:

```

python certificado.py


```

3. Os certificados serão gerados e salvos como arquivos de imagem PNG no mesmo diretório.
