# Calculadora de IMC

Este projeto é uma *Calculadora de IMC* (Índice de Massa Corporal) simples, desenvolvida com o objetivo de praticar conceitos de programação e aprimorar as habilidades de desenvolvimento *front-end*. O projeto faz parte da formação de programador front-end, onde são aplicadas técnicas de HTML, CSS e JavaScript.


## Índice



- [Objetivo](#objetivo)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Objetivo

O objetivo deste projeto é desenvolver uma calculadora que permita o usuário calcular seu IMC de forma prática e intuitiva, consolidando os conceitos de:
- Estruturação de páginas com *HTML*;
- Estilização com *CSS*;
- Programação de funcionalidades interativas com *JavaScript*.

Além disso, o projeto segue boas práticas de codificação e é um exemplo prático para aprender e demonstrar a lógica por trás de uma aplicação de front-end.

## Funcionalidades

- Input para o usuário inserir seu *peso* (em kg) e *altura* (em metros).
- Botão de calcular que exibe o *IMC* e a respectiva *classificação* de acordo com as faixas definidas pela Organização Mundial da Saúde:
  - Abaixo do peso
  - Peso normal
  - Sobrepeso
  - Obesidade grau 1, 2 ou 3
- Interface responsiva e amigável para diferentes dispositivos.

### Home Page  
  
![Página Inicial](./assets/screenshots/Home%20Page.jpg)
![Página em ação](assets/screenshots/Calculadora%20IMC.gif)  

## Tecnologias Utilizadas

- *HTML5*: Para a estruturação da página.
- *CSS3*: Para estilizar e tornar a interface agradável e responsiva.
- *JavaScript*: Para a lógica de cálculo do IMC e interação com o usuário.

## Como Executar o Projeto

1. *Clone o repositório*:
   ```bash
   git clone https://github.com/adrianovital-dev/calculadora-imc.git
   ```

2. *Acesse a pasta do projeto*:
   ```bash
   cd calculadora-imc
   ```

3. *Abra o arquivo index.html no navegador*:
   - Você pode abrir o arquivo diretamente clicando nele no seu explorador de arquivos ou executando um servidor local para servir a aplicação.

### Exemplo de Execução com Live Server (VS Code):
1. Instale a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) no VS Code.
2. Clique com o botão direito no arquivo index.html e selecione *"Open with Live Server"*.

## Estrutura de Arquivos

  ```bash
calculadora-imc/
├── index.html          # Página principal com a interface da 
├── styles.css          # Estilos para a página
├── script.js           # Lógica de cálculo do IMC
├── Imagens             # Imagens da aplicação
├── screenshots         # Screenshots da aplicação
└── README.md           # Arquivo de documentação do projeto
```

## Contribuição

Sinta-se à vontade para contribuir com o projeto, seja com melhorias de código, design ou funcionalidades adicionais. Para isso, siga os passos:

1. *Fork o projeto*.
2. Crie uma nova branch com sua feature (git checkout -b feature/minha-feature).
3. Faça o commit das suas mudanças (git commit -m 'Adicionar minha feature').
4. Envie a branch (git push origin feature/minha-feature).
5. Abra um *Pull Request*.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
