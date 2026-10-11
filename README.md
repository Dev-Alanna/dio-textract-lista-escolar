# Extração de Texto de Lista Escolar com AWS Textract

Projeto prático desenvolvido para o bootcamp da **DIO** para demonstrar o uso do serviço de Inteligência Artificial **Amazon Textract** na extração de texto a partir de uma imagem de lista de materiais escolares.

---

## Objetivo

Demonstrar na prática como funciona a tecnologia de OCR (Reconhecimento Óptico de Caracteres) na nuvem da AWS. O objetivo foi converter uma imagem de uma lista escolar física em dados de texto digital que podem ser lidos, copiados e pesquisados no computador.

---

## Tecnologias Utilizadas

- **Amazon Textract:** Serviço de IA da AWS que lê e extrai textos e linhas de imagens.
- **Python / Boto3:** Linguagem e biblioteca utilizadas na demonstração para conectar com a AWS.
- **Gerenciador UV:** Ferramenta para instalar dependências do projeto rapidamente.

---

##  Como Funciona o Processo

1. **Imagem de Entrada:** Uma imagem contendo uma lista de materiais escolares (como cadernos, lápis, borrachas e canetas).
2. **Envio para a AWS:** A imagem é enviada para a função `DetectDocumentText` do Amazon Textract.
3. **Leitura Inteligente:** O Textract analisa os pixels, identifica os caracteres e agrupa as palavras em linhas completas.
4. **Resultado:** O texto da lista é impresso no terminal, linha por linha, preservando a ordem dos itens.

---

##  Aprendizados e Insights

- **Sem digitação manual:** O Textract lê listas e papéis em segundos, eliminando o trabalho de digitar documento por documento.
- **Identificação de Linhas:** Ele não joga palavras soltas na tela; ele entende quais palavras pertencem à mesma linha da lista.
- **Aplicações no Mercado:** Esse mesmo processo pode ser usado para ler notas fiscais, cupons de compras, pedidos de restaurantes e receitas médicas.

---

Bootcamp Nublify - Primeiros passos em IA e Cloud (DIO).
