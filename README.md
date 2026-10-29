<div align="center">

# URNA DIGITAL 2026

### Simulação interativa de votação eletrônica

Uma aplicação web desenvolvida para simular a experiência de votação em uma urna eletrônica, com interface responsiva, identificação de candidatos e apuração de resultados em tempo real.

<br>

![HTML5](https://img.shields.io/badge/HTML5-Estrutura-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-Estilização-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Interatividade-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Em_desenvolvimento-16852A?style=flat-square)

</div>

---

## Sobre o projeto

A **Urna Digital 2026** é um projeto de desenvolvimento web que reproduz, de maneira demonstrativa, os principais elementos de uma interface de votação eletrônica.

A aplicação permite selecionar candidatos por meio de um teclado numérico, conferir as informações apresentadas na tela, confirmar votos e acompanhar uma apuração visual dos resultados.

O projeto foi desenvolvido com tecnologias fundamentais do desenvolvimento front-end, priorizando a simplicidade de execução, a interatividade e a adaptação a diferentes dispositivos.

## Funcionalidades

- **Interface de votação:** layout inspirado em urnas eletrônicas.
- **Identificação de candidatos:** exibição das informações correspondentes ao número digitado.
- **Registro de votos:** confirmação de votos durante a simulação.
- **Voto em branco:** opção de registrar votos em branco.
- **Correção de entrada:** possibilidade de corrigir o número antes da confirmação.
- **Apuração dinâmica:** atualização da quantidade e do percentual de votos.
- **Visualização gráfica:** barras de progresso para representar os resultados.
- **Efeitos sonoros:** sons eletrônicos gerados pela Web Audio API.
- **Controles pelo teclado:** suporte a teclas físicas do computador.
- **Design responsivo:** adaptação da interface para diferentes tamanhos de tela.
- **Reinicialização:** opção para zerar os resultados e iniciar uma nova simulação.

## Tecnologias

| Tecnologia | Aplicação |
|---|---|
| HTML5 | Estrutura e organização dos elementos |
| CSS3 | Layout, estilização, animações e responsividade |
| JavaScript | Regras de votação, eventos e atualização da interface |
| Web Audio API | Geração de efeitos sonoros pelo navegador |

O projeto utiliza tecnologias nativas da web, sem necessidade de frameworks ou bibliotecas externas para sua funcionalidade principal.

## Como executar

### Requisitos

- Navegador atualizado.
- Git, caso queira clonar o repositório.

### Execução local

Clone o repositório:

```bash
git clone URL_DO_SEU_REPOSITORIO
```

Entre na pasta do projeto:

```bash
cd NOME_DO_REPOSITORIO
```

Abra o arquivo `index.html` em seu navegador.

**Importante:** substitua `URL_DO_SEU_REPOSITORIO` e `NOME_DO_REPOSITORIO` pelos dados reais do seu projeto.

Não é necessária uma instalação de dependências para executar a versão básica.

## Como utilizar

1. Abra a aplicação no navegador.
2. Digite o número de um dos candidatos disponíveis.
3. Confira as informações exibidas na tela.
4. Se necessário, utilize a opção de correção.
5. Pressione **CONFIRMA** para registrar o voto.
6. Para registrar um voto em branco, selecione **BRANCO** e confirme.
7. Consulte a apuração apresentada durante a simulação.

O teclado físico também pode ser utilizado para digitar números, confirmar operações e corrigir a entrada.

## Apuração dos resultados

Os resultados são calculados a partir dos votos registrados durante a sessão.

A interface apresenta:

- Quantidade de votos por opção.
- Percentual de cada opção em relação ao total.
- Total de votos registrados.
- Representação visual dos resultados por meio de barras.

Os dados são armazenados em memória durante a execução da página. Portanto, não existe persistência em banco de dados, e os resultados podem ser perdidos ao recarregar a aplicação.

## Estrutura do projeto

```text
Urna-Digital-2026/
├── index.html
├── README.md
└── img/
    └── Ruan.png
```

A estrutura acima é ilustrativa. Os arquivos devem corresponder à organização real do repositório.

## Objetivos de desenvolvimento

Este projeto permite aplicar conhecimentos de:

- Estruturação semântica com HTML.
- Estilização e responsividade com CSS.
- Manipulação do DOM com JavaScript.
- Tratamento de eventos e interações.
- Organização e atualização de dados.
- Cálculo de totais e percentuais.
- Geração de áudio com recursos nativos do navegador.
- Desenvolvimento de interfaces acessíveis e intuitivas.

## Próximas melhorias

- [ ] Separar HTML, CSS e JavaScript em arquivos independentes.
- [ ] Aprimorar os recursos de acessibilidade.
- [ ] Implementar uma tela de encerramento da votação.
- [ ] Adicionar exportação dos resultados.
- [ ] Expandir as opções de configuração da simulação.
- [ ] Aprimorar os testes em dispositivos móveis.
- [ ] Desenvolver novos recursos para a visualização da apuração.

## Aviso importante

Esta aplicação é exclusivamente educacional e demonstrativa.

Não é um sistema oficial de votação, não possui vínculo com o Tribunal Superior Eleitoral (TSE) e não deve ser utilizada para eleições reais.

Os candidatos e os resultados apresentados fazem parte de uma simulação, sem valor eleitoral oficial.

## Autor

**Samuel Moysés**

Estudante de desenvolvimento de sistemas, com interesse em programação, desenvolvimento web e criação de aplicações interativas.

---

<div align="center">

Desenvolvido com HTML, CSS e JavaScript.

**Urna Digital 2026 | Projeto educacional**

</div>
