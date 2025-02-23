# Projeto de Resolução de Exercícios com Node.js e TypeScript  

Este projeto foi desenvolvido para resolver uma série de exercícios utilizando Node.js e TypeScript, seguindo uma estrutura organizada com classes e serviços. Cada problema foi implementado de forma modular e reutilizável, com foco na clareza e manutenção do código.  

## 📜 Descrição do Projeto  

O projeto consiste na solução de cinco exercícios, incluindo cálculo de soma, verificação da sequência de Fibonacci, e outros desafios relacionados a algoritmos e lógica de programação.  

Cada funcionalidade foi implementada como um serviço independente, permitindo fácil expansão e integração de novas funcionalidades.  

---

## 🛠️ Tecnologias Utilizadas  

- **Node.js**  
- **TypeScript**  
- **ts-node** (para execução de arquivos TypeScript sem compilação explícita)

---

## 📂 Estrutura do Projeto  

```plaintext
.
├── src
│   ├── data
│   ├── models
│   ├── services
│   │   ├── soma.service.ts       # Serviço para cálculo de soma (Exercício 1)
│   │   ├── fibonacci.service.ts  # Serviço para verificar sequência de Fibonacci (Exercício 2)
│   │   └── outros serviços...    # Serviços adicionais
│   ├── app.ts                    # Ponto de entrada do projeto
├── package.json                  # Dependências e scripts do projeto
├── tsconfig.json                 # Configurações do TypeScript
└── README.md                     # Documentação do projeto
```

## 🚀 Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado em sua máquina:

- **Node.js** (versão 18 ou superior)
- **npm**

### Passo a Passo

1. Clone o repositório:
   ```bash
   git clone git@github.com:GabrielaMoura05/TargetSistemas.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd distribuidora-faturamento
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Para executar o projeto:
   ```bash
   npx ts-node src/app.ts
   ```

## ✨ Contribuições  
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.  

## 📝 Licença  
Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais detalhes.  

## 👩‍💻 Desenvolvedor  
Feito com ❤️ por Gabriela Moura.  
