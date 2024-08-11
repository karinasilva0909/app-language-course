# App Language Course

Este é um projeto de exemplo de um aplicativo de curso de língua estrangeira construído com ReactJS e TypeScript.

## Estrutura do Projeto

A estrutura do projeto foi organizada para garantir uma fácil manutenção e escalabilidade. Abaixo está uma descrição dos principais diretórios e arquivos:

app-language-course/
├── node_modules/ # Dependências do projeto
├── public/ # Arquivos públicos, como index.html e ícones
├── src/ # Código-fonte da aplicação
│ ├── assets/ # Arquivos estáticos como imagens e estilos globais
│ ├── components/ # Componentes reutilizáveis (Button, Header, Footer, etc.)
│ ├── context/ # Context API para gerenciamento de estado global
│ ├── hooks/ # Custom hooks para lógica reutilizável
│ ├── pages/ # Páginas principais da aplicação (Home, Course, etc.)
│ ├── services/ # Serviços para lógica de negócios e integração com API
│ ├── App.tsx # Componente principal da aplicação
│ ├── index.tsx # Ponto de entrada da aplicação
│ └── ...
├── .gitignore # Arquivos e diretórios ignorados pelo Git
├── package.json # Dependências e scripts do projeto
├── tsconfig.json # Configurações do TypeScript
└── yarn.lock # Arquivo de bloqueio de dependências gerado pelo Yarn


### Descrição das Pastas

- **assets/**: Contém arquivos estáticos como imagens, ícones, e estilos globais.
- **components/**: Armazena componentes reutilizáveis, que podem ser usados em diferentes partes da aplicação.
- **context/**: Contém arquivos relacionados à Context API, usada para gerenciamento de estado global.
- **hooks/**: Custom hooks que encapsulam lógica reutilizável.
- **pages/**: Contém os componentes de página principais da aplicação, cada página representa uma rota na aplicação.
- **services/**: Arquivos responsáveis pela lógica de negócios e chamadas a APIs externas.

## Padrões de Arquitetura

- **Componentes Funcionais e Hooks**: A aplicação é composta por componentes funcionais, utilizando hooks para gerenciar o estado e efeitos colaterais.
- **Composição de Componentes**: Promovemos a composição de componentes para maximizar a reutilização e a manutenibilidade.
- **Context API**: Utilizada para compartilhar estado global sem a necessidade de prop drilling.
- **Code Splitting e Lazy Loading**: Implementado para melhorar o desempenho da aplicação, carregando componentes apenas quando necessário.
- **Single Responsibility Principle (SRP)**: Cada componente tem uma única responsabilidade, facilitando testes e manutenção.

## Pré-requisitos

Antes de começar, certifique-se de ter o [Node.js](https://nodejs.org/) e o [Yarn](https://yarnpkg.com/) instalados em sua máquina.

## Instalação

Siga os passos abaixo para configurar e executar o projeto localmente:

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu-usuario/app-language-course.git
   cd app-language-course
