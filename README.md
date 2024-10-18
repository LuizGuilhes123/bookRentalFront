# bookRental-vue

### Descrição do Projeto
O bookRental-vue é um sistema de biblioteca online desenvolvido com Vue.js, que permite a gestão de livros, usuários, editoras e aluguéis, com uma interface de dashboard para visualização e controle. O projeto possui funcionalidades de CRUD (Criar, Ler, Atualizar e Deletar) para livros, usuários, aluguéis e editoras, além de regras de negócio para garantir a integridade dos dados e processos. Por exemplo, um usuário não pode ser deletado enquanto tiver um aluguel pendente, e um livro só pode ser cadastrado se estiver associado a uma editora.

### Configuração do Projeto
Para configurar o projeto localmente, siga as instruções abaixo.

### Instalação das dependências
Execute o comando a seguir para instalar todas as dependências do projeto:

## Instalação de depedencias
```
npm install
```

### Compilação e recarga automática para desenvolvimento
```
npm run serve
```

### Compilação e minificação para produção
```
npm run build
```

### Verificação e correção de problemas de lint
```
npm run lint
```

### Personalização da configuração
See [Configuration Reference](https://cli.vuejs.org/config/).

### Observação
Este projeto foi desenvolvido como parte de um trabalho acadêmico para a Unifametro e foi realizado por Luiz Guilherme de Sousa Braga.
