# Analisador de Tétrades

Aplicativo web em HTML único para análise de possíveis interpretações harmônicas de tétrades em contexto tonal.

O app permite escolher uma tonalidade maior, selecionar o tipo de tétrade e tocar a fundamental em um teclado de piano de uma oitava. A análise é exibida imediatamente, mostrando as possíveis interpretações do acorde conforme o contexto tonal.

<img width="844" height="671" alt="image" src="https://github.com/user-attachments/assets/278fa112-2e0d-4b5f-8e32-6c9900036a81" />


## Funcionalidades

- Seleção de tonalidade maior, com padrão em Dó maior.
- Escolha dos tipos de tétrade:
  - Maj7
  - 7
  - m7
  - m7(b)
  - dim7
- Teclado de piano de uma oitava para escolha da fundamental.
- Alternância enarmônica nas teclas pretas.
- Execução sonora da nota ou acorde escolhido pelo navegador.
- Modo claro e modo escuro.
- Texto explicativo acessível por botão de explanação.
- Base de dados embutida no próprio HTML, sem dependência de servidor ou arquivos externos.

## Como usar

1. Abra o arquivo `analisador_de_tetrades_v11.html` no navegador.
2. Escolha a tonalidade.
3. Escolha o tipo de tétrade.
4. Clique na fundamental desejada no teclado.
5. Leia as possíveis interpretações no campo **Análise**.

Quando uma fundamental é indicada com grafia enarmônica inadequada para a tonalidade, o app considera a equivalência sonora e realiza a análise com a grafia mais apropriada ao contexto tonal.

## Requisitos

O app funciona diretamente no navegador e não precisa de instalação.

Recomenda-se usar uma versão recente de:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari

O som é gerado pelo próprio navegador por meio da Web Audio API. Alguns navegadores só liberam áudio depois do primeiro clique do usuário na página.

## Créditos

Concepção inicial: Glauber Santiago e Terence Santos

Desenvolvido pelo professor Glauber Santiago — DAC/UFSCar

servidores.ufscar.br/glauber/  
sites.google.com/view/glauberia

## Licença

Defina aqui a licença de uso do projeto antes de publicar o repositório.

Sugestão: caso deseje permitir uso, cópia e adaptação com atribuição, considere uma licença como MIT ou Creative Commons, conforme o objetivo do projeto.
