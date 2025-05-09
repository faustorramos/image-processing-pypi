# Comparador de Imagens em Python

Este projeto permite comparar duas imagens e gerar uma terceira imagem que destaca as diferencas em preto e branco. Ele utiliza a biblioteca **Pillow** para a manipulacao de imagens e inclui tratamento robusto de erros para garantir uma execucao confiavel.

## Indice

- [Descricao](#descricao)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalacao](#instalacao)
- [Uso](#uso)
- [Exemplo de Execucao](#exemplo-de-execucao)
- [Contribuicao](#contribuicao)
- [Licenca](#licenca)

## Descricao

O projeto e composto por dois modulos principais:

1. `__init__.py`: Realiza o carregamento, comparacao e salvamento das imagens processadas.
2. `comparar_imagens.py`: Contem funcoes para carregar imagens, identificar diferencas entre elas e salvar a imagem resultante.

## Funcionalidades

- Carrega duas imagens a partir de caminhos fornecidos.
- Compara as imagens e gera uma nova imagem que destaca as diferencas.
- Salva a imagem gerada em um caminho especificado.
- Lida com excecoes, como arquivos ausentes ou incompatibilidades entre as imagens.

## Requisitos

Certifique-se de que o ambiente Python possua os seguintes requisitos:

- Python 3.7 ou superior.
- Biblioteca Pillow instalada.
- Imagens de entrada com o mesmo tamanho e formato.

## Instalacao

1. Clone este repositorio:

   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio

2. Instale a biblioteca Pillow:

	pip install pillow

## Uso

1. Coloque as imagens que deseja comparar na pasta img e renomeie para img1.jpg e img2.jpg

2. Execute o script __init__.py

	python __init__.py

3. A imagem com as diferencas sera gerada no caminho especificado no codigo.

## Exemplo de Execucao

Suponha que você tenha dusas imagens nomeadas como img1.jpg e img2.jpg na pasta img. Ao executar o comando:

	python __init__.py

Sera gerada uma nova imagem chamada imagem_diferencas.png contendo as diferencas destacadas em preto e branco.

## Contribuicao

Sinta-se à vontade para contribuir com este projeto. Abra uma issue para relatar bugs ou sugerir melhorias, ou envie um pull request.

## Licenca

Este projeto esta licenciado sob a licenca MIT. Consulte o arquivo LICENSE para mais detalhes.
