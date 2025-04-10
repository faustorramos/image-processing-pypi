# Comparador de Imagens em Python

Este projeto permite comparar duas imagens e gerar uma terceira imagem que destaca as diferenças em preto e branco. Ele utiliza a biblioteca **Pillow** para a manipulação de imagens e inclui tratamento robusto de erros para garantir uma execução confiável.

## Indice

- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
- [Requisitos](#requisitos)
- [Instalação](#instalação)
- [Uso](#uso)
- [Exemplo de Execução](#exemplo-de-execução)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Descrição

O projeto é composto por dois módulos principais:

1. `__init__.py`: Realiza o carregamento, comparação e salvamento das imagens processadas.
2. `comparar_imagens.py`: Contém funções para carregar imagens, identificar diferenças entre elas e salvar a imagem resultante.

## Funcionalidades

- Carrega duas imagens a partir de caminhos fornecidos.
- Compara as imagens e gera uma nova imagem que destaca as diferenças.
- Salva a imagem gerada em um caminho especificado.
- Lida com exceções, como arquivos ausentes ou incompatibilidades entre as imagens.

## Requisitos

Certifique-se de que o ambiente Python possua os seguintes requisitos:

- Python 3.7 ou superior.
- Biblioteca Pillow instalada.
- Imagens de entrada com o mesmo tamanho e formato.

## Instalação

1. Clone este repositório:

   git clone https://github.com/seu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio

2. Instale a biblioteca Pillow:

	pip install pillow

## Uso

1. Coloque as imagens que deseja comparar na pasta img e renomeie para img1.jpg e img2.jpg

2. Execute o script __init__.py

	python __init__.py

3. A imagem com as diferenças será gerada no caminho especificado no código.

## Exemplo de Execução

Suponha que voçê tenha dusas imagens nomeadas como img1.jpg e img2.jpg na pasta img. Ao executar o comando:

	python __init__.py

Será gerada uma nova imagem chamada imagem_diferencas.png contendo as diferenças destacadas em preto e branco.

## Contribuição

Sinta-se à vontade para contribuir com este projeto. Abra uma issue para relatar bugs ou sugerir melhorias, ou envie um pull request.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.
