# Text To Voice

![site_cafeteria.svg](https://github.com/FernandoJesuss/Text_To_Voice/blob/main/img/hometexttovoice.svg)

[Link do Projeto]() <br>



Descrição do Projeto | Funcionalidades | Tecnologias Utilizadas | Como Usar | Estrutura de Arquivos | Possíveis Melhorias | Créditos

# Descrição do Projeto
O Conversor de Texto para Voz é uma aplicação web que permite ao usuário digitar ou enviar um texto, selecionar uma voz e ouvir a leitura desse texto. O objetivo é facilitar a conversão de texto escrito em áudio, tornando o conteúdo mais acessível para pessoas com deficiência visual ou para quem prefere consumir informações de forma auditiva.


# Funcionalidades
Entrada de Texto: Campo para digitação de texto ou envio de arquivo contendo texto.

Envio de Arquivo: Botão para upload de arquivos de texto.

Seleção de Voz: Opção para escolher a voz de leitura (exemplo: Microsoft Daniel – Português).

Ouvir Texto: Botão para ouvir o texto digitado ou enviado.

Download: Opção para baixar o texto.

# Tecnologias Utilizadas
Frontend: HTML5| CSS3 | JavaScript

APIs: Web Speech API (ou outra API de síntese de voz)

Design: Interface minimalista e responsiva

# Como Usar
Digite um texto no campo principal ou envie um arquivo clicando em “Enviar arquivo”.

Selecione a voz desejada no menu suspenso.

Clique em “Ouvir” para escutar o texto convertido em voz.

Para baixar o texto, clique em “Baixar Texto”.

````
/
├── index.html        # Página principal da aplicação
├── style.css         # Estilos da interface
├── script.js         # Lógica de conversão e interação
├── assets/           # Imagens e outros recursos (ex: microfone)

````
# Possíveis Melhorias
Suporte a múltiplos idiomas e vozes.

Geração e download de arquivos em formato MP3.

Histórico de textos convertidos.

Interface adaptada para dispositivos móveis.

Integração com serviços de nuvem para armazenar áudios gerados.
