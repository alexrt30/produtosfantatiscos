# produtosfantatiscos
Este projeto é uma aplicação web simples para cadastrar e listar produtos, seguindo um estilo de layout inspirado no Shopee. Ele foi dividido em duas telas principais:
Segue abaixo um **modelo de descrição** (ou resumo) do projeto, em português, que pode ser usado em README ou apresentação:

---

## Descrição do Projeto

Este projeto é uma aplicação web simples para **cadastrar** e **listar** produtos, seguindo um estilo de layout inspirado na Shopee. Ele foi dividido em duas telas principais:

1. **Tela de Cadastro** (`index.html`):  
   - Permite inserir **Nome**, **Código** e **Link** do produto.  
   - Armazena as informações no **localStorage** do navegador ou em um **banco de dados** (caso a aplicação seja integrada a serviços como Supabase ou Firebase).  
   - Ao cadastrar, os campos são limpos e é exibida uma mensagem de sucesso.  

2. **Tela de Listagem** (`lista.html`):  
   - Exibe todos os produtos cadastrados em forma de tabela.  
   - Possui um **campo de busca** que filtra os resultados por **nome** ou **código**.  
   - Cada produto exibe seu **link**, que pode ser aberto em uma nova aba ao clicar.  

### Funcionalidades Principais

- **Cadastro de produtos** com campos obrigatórios (Nome, Código e Link).  
- **Armazenamento** local (via `localStorage`) ou em um banco remoto (exemplo: [Supabase](https://supabase.com/)), de forma simples.  
- **Listagem** dos produtos em tabela, com estilo responsivo básico.  
- **Busca/Filtragem** em tempo real, para encontrar produtos por nome ou código.  

### Tecnologias Utilizadas

- **HTML5** e **CSS3**: Estrutura e estilos das páginas.  
- **JavaScript**:  
  - Manipulação do DOM para exibir e filtrar a lista de produtos.  
  - Armazenamento e recuperação de dados do localStorage (ou chamadas a uma API externa, como a do Supabase).  
- **GitHub Pages** (ou outro serviço de hospedagem como Netlify/Vercel): Hospedagem gratuita das páginas estáticas.  
- (Opcional) **Supabase** ou **Firebase**: Integração com um banco de dados na nuvem, permitindo salvar e buscar os registros online.  

### Como Executar

1. **Baixe ou clone** o repositório.  
2. Abra o arquivo `index.html` em um navegador para realizar o cadastro.  
3. Abra o arquivo `lista.html` para visualizar a listagem com busca.  
4. (Opcional) Para hospedar no **GitHub Pages** ou outro serviço, suba todos os arquivos (HTML, CSS, JS) para o repositório e ative o recurso de hospedagem estática.

### Próximos Passos

- Adicionar **validações** mais avançadas, como garantir que não sejam cadastrados produtos repetidos ou vazios.  
- Integrar com um **backend** ou serviço de banco de dados (Supabase, Firebase, etc.) para permitir acesso multiusuário.  
- Implementar **edição** e **exclusão** de produtos já cadastrados.  
- Adicionar **autenticação** de usuário, se necessário.  
