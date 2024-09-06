# Desafio de Ransomware - DIO Cybersecurity

## Descrição

Este repositório contém um desafio de cibersegurança focado em ransomware, parte do curso de cibersegurança da DIO. O objetivo do desafio é criar um ransomware que criptografe e descriptografe um arquivo de teste chamado `teste.txt`.

## Objetivo do Desafio

- **Criptografar** o arquivo `teste.txt` usando um algoritmo de criptografia AES.
- **Descriptografar** o arquivo criptografado para restaurar o arquivo original.

## Estrutura do Repositório

- **`encripter.py`**: Script para criptografar o arquivo `teste.txt`.
- **`decripter.py`**: Script para descriptografar o arquivo criptografado.
- **`teste.txt`**: Arquivo de teste a ser criptografado e descriptografado.

## Pré-requisitos

Certifique-se de ter o Python 3 e a biblioteca `pyaes` instalada. Você pode instalar a biblioteca necessária com:

```bash
pip install pyaes
