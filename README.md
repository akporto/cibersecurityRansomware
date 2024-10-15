# Ransomware com Python

Este projeto demonstra a criação de um ransomware simples utilizando Python e a biblioteca `pyaes`. O ransomware criptografa um arquivo de texto e oferece a capacidade de descriptografá-lo usando a chave de criptografia correta. **Atenção**: Este projeto é apenas para fins educacionais e de pesquisa. Utilizar ransomware ou outras formas de malware de forma mal-intencionada é ilegal e antiético.

## Requisitos

- **Python 3.x**
- **Biblioteca `pyaes`**: Para instalação, utilize o comando:
  
  pip install pyaes

## Funcionalidades

Criptografia de Arquivo: O programa lê o conteúdo de um arquivo (teste.txt), o criptografa usando uma chave pré-definida e remove o arquivo original. O resultado é salvo em um novo arquivo com a extensão .ransomwaretroll.

Descriptografia de Arquivo: O programa permite a descriptografia do arquivo criptografado, recriando o arquivo original a partir dos dados criptografados.

## Funcionamento
Processo de Criptografia:

O arquivo de texto é aberto e seu conteúdo é lido.
Após a leitura, o arquivo original é removido.
O conteúdo é criptografado com uma chave específica e salvo como um novo arquivo.
Processo de Descriptografia:

O arquivo criptografado é aberto e seu conteúdo é lido.
Usando a mesma chave de criptografia, o conteúdo é descriptografado.
O arquivo criptografado é removido e o arquivo original é recriado.

##Como Usar

Coloque um arquivo chamado teste.txt na mesma pasta do script Python.
Execute o código de criptografia para criptografar o arquivo e gerar o arquivo .ransomwaretroll.
Execute o código de descriptografia para restaurar o arquivo original a partir do arquivo criptografado.

##Execução do Script:

Para criptografar o arquivo:

python ransomware.py

Para descriptografar o arquivo:

python decrypt.py
