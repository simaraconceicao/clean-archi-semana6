````
src/
│
├── application/
│   ├── repositories/
│   │   └── book-repository.ts // Interface do repositório
│   │   └── id-generator-interface.ts // Interface do gerador de id
│   └── use-cases/
│       ├── create-book-use-case.ts
│       ├── list-all-books-use-case.ts
│       ├── update-book-use-case.ts
│       └── delete-book-use-case.ts
│
├── domain/
│   └── book.ts                // Interface do domínio Book
│
├── infrastructure/
│   ├── database/
│   │   └── repository.ts      // Implementação do repositório
│   └── utils/
│       └── config.ts          // Configuração de dependências
│       └── id-generator.ts   //  implementação da interface de gerar ID
│
├── interface/
│   └── book-controller.ts     // Controlador que lida com as requisições HTTP
|   ├── index.ts              // Arquivo principal da aplicação
│

````