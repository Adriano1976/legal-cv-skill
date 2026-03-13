# Legal CV Skill

Skill projetada para processar currículos profissionais e gerar uma seção de Habilidades estratégica e orientada a resultados.

## Tecnologias Utilizadas

- **JavaScript** - Linguagem de programação
- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web
- **MongoDB** - Banco de dados NoSQL
- **Jest** - Framework de testes
- **Markdown** - Formatação de documentação

## Como Configurar e Rodar

### Pré-requisitos
- Node.js (versão 14 ou superior)
- npm ou yarn
- MongoDB instalado e rodando

### Passos de Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Adriano1976/legal-cv-skill.git
   cd legal-cv-skill
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Configure as variáveis de ambiente:**
   Crie um arquivo `.env` na raiz do projeto com as configurações necessárias:
   ```
   DATABASE_URL=mongodb://localhost:27017/legal-cv-skill
   PORT=3000
   NODE_ENV=development
   ```

4. **Inicie a aplicação:**
   ```bash
   npm start
   ```

## Como Testar

### Executar todos os testes:
```bash
npm test
```

### Executar testes em modo watch:
```bash
npm test -- --watch
```

### Executar testes com cobertura:
```bash
npm test -- --coverage
```

## Estrutura do Projeto

```
legal-cv-skill/
├── assets/           # Arquivos de template e recursos
├── references/       # Documentação de referência
├── scripts/          # Scripts utilitários
├── src/              # Código fonte
├── tests/            # Testes unitários
├── README.md         # Este arquivo
├── SKILL.md          # Documentação da skill
└── package.json      # Dependências do projeto
```

## Uso

A skill processa um currículo e contexto profissional do usuário para gerar uma seção de **Habilidades** altamente estratégica e atrativa para recrutadores.

### Exemplo de Uso:
```javascript
const skill = require('./src/legal-cv-skill');
const result = skill.generateSkills(curriculum, professionalContext);
```

## Documentação Adicional

- Veja `SKILL.md` para detalhes sobre as regras de geração de habilidades
- Consulte `references/termos_recrutadores.md` para verbos e termos valorizados

## Contribuindo

Contribuições são bem-vindas! Por favor, abra uma issue ou pull request com suas sugestões.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.