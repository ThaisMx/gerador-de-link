# Gerador de Links Cronnos

## Visão Geral

Este projeto é um gerador de links UTM para checkout, criado para facilitar a geração de URLs personalizadas para diferentes campanhas de marketing. O usuário pode preencher informações específicas, como funil, campanha, SDR e Closer, e o aplicativo gerará um link contendo os parâmetros UTM com as informações selecionadas.

## Funcionalidades

- Interface amigável para gerar links UTM personalizados.
- Opção de copiar o link gerado com um clique.
- Validação para garantir que todos os campos obrigatórios sejam preenchidos.
- Responsividade para ser utilizado em dispositivos móveis.

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **CSS3**: Estilização da interface, com suporte a responsividade.
- **JavaScript**: Lógica para geração de links, manipulação do DOM e cópia para a área de transferência.

## Como Usar

1. Clone o repositório para o seu computador:
   ```bash
   git clone <link-do-repositorio>
   ```
2. Abra o arquivo `index.html` no seu navegador.
3. Preencha os campos obrigatórios:
   - **Link do Checkout**: URL base do checkout.
   - **Funil**: Selecione o tipo de funil.
   - **Campanha**: (Opcional, mas obrigatório para o funil "Lançamento").
   - **SDR**: Selecione o SDR.
   - **Closer**: Selecione o Closer.
4. Clique no botão "Gerar Link" para gerar o link UTM.
5. Clique no ícone de copiar ao lado do link gerado para copiá-lo para a área de transferência.

## Estrutura do Projeto

- `index.html`: Estrutura principal da aplicação.
- `styles.css`: Estilização da página, incluindo temas escuros e responsividade.
- `script.js`: Lógica do JavaScript para geração do link e interação do usuário.

## Responsividade

Este projeto foi projetado para ser totalmente responsivo, garantindo uma experiência de usuário suave tanto em desktops quanto em dispositivos móveis. A interface ajusta-se automaticamente ao tamanho da tela, proporcionando um uso confortável em qualquer dispositivo.

## Créditos

Feito com ♥ por Thais M.

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou novas funcionalidades. Basta abrir uma *pull request* ou relatar problemas na página de *issues* do repositório.

## Licença

Este projeto está licenciado sob a licença MIT. Sinta-se à vontade para usá-lo e modificá-lo conforme necessário.

