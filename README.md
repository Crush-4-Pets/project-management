# Dashboard de Gerenciamento do Projeto Crush4Pets

## Visão Geral

Este repositório contém o dashboard de gerenciamento do projeto Crush4Pets, uma ferramenta visual para acompanhamento do roadmap, sprints, tarefas e progresso geral do desenvolvimento. O dashboard apresenta informações detalhadas sobre o planejamento, execução e monitoramento do projeto Crush4Pets.

## Estrutura do Projeto

O ecossistema Crush4Pets consiste em múltiplos componentes integrados:

1. **Banco de Dados**
   - Suporte para armazenamento de dados e informações geoespaciais
   - Utilizado por todos os serviços do ecossistema

2. **Backend API**
   - Aplicação baseada em PHP Symfony
   - Provê endpoints RESTful API e suporte GraphQL

3. **Serviço de Upload de Arquivos**
   - Microserviço para gerenciamento de arquivos
   - Responsável pelo armazenamento em nuvem

4. **Aplicação ERP**
   - Interface principal para usuários finais
   - Dashboard para operações de negócio

## Metodologia de Desenvolvimento

O projeto utiliza uma metodologia ágil com sprints semanais:

1. **Sprint 1: Configuração Inicial** (31 de Março - 7 de Abril de 2025)
   - Kick-off do projeto
   - Criação da estrutura organizacional no GitHub
   - Setup do ambiente de desenvolvimento

2. **Sprint 2: CI/CD & Correção de Bugs** (8 de Abril - 14 de Abril de 2025)
   - Implementação de pipeline CI/CD
   - Resolução de bugs críticos
   - Implementação de novas funcionalidades

3. **Sprint 3: Submissão para as Lojas** (15 de Abril - 21 de Abril de 2025)
   - Preparação para submissão nas lojas
   - Testes finais
   - Documentação

4. **Sprint 4: Implementação de Feedback das Lojas** (22 de Abril - 28 de Abril de 2025)
   - Ajustes baseados no feedback das lojas
   - Resubmissão das aplicações
   - Garantia de qualidade

## Como Visualizar o Dashboard

### Opção 1: Visualização Online no GitHub Pages

Para visualizar o dashboard online:

1. Acesse o link: https://crush-4-pets.github.io/project-management/
2. Navegue pelas diferentes seções do dashboard para ver o progresso das sprints e tarefas

### Opção 2: Visualização Local

Para visualizar o dashboard localmente:

1. Clone o repositório:
   ```bash
   git clone https://github.com/Crush-4-Pets/project-management.git
   ```

2. Navegue até o diretório do projeto:
   ```bash
   cd project-management
   ```

3. Abra o arquivo `index.html` em qualquer navegador:
   ```bash
   open index.html  # macOS
   # OU
   xdg-open index.html  # Linux
   # OU
   start index.html  # Windows
   ```

## Atualização do Dashboard

Para contribuir com atualizações no dashboard:

1. Clone o repositório (se ainda não tiver feito):
   ```bash
   git clone https://github.com/Crush-4-Pets/project-management.git
   ```

2. Crie uma branch para suas alterações:
   ```bash
   git checkout -b atualizacao-dashboard
   ```

3. Faça as alterações necessárias no arquivo `index.html`

4. Atualize o status das tarefas conforme necessário (alterando a classe CSS de `pending` para `completed`)

5. Commit e push das alterações:
   ```bash
   git add .
   git commit -m "Atualização: descrição das alterações"
   git push origin atualizacao-dashboard
   ```

6. Crie um Pull Request no GitHub para mesclar suas alterações

## Interpretação do Gráfico Burndown

O gráfico burndown exibe:

- **Linha Azul**: Progressão ideal do projeto (redução planejada de story points)
- **Linha Laranja**: Progressão real do projeto (redução efetiva de story points)

Uma linha real abaixo da linha ideal indica que o projeto está adiantado. Uma linha real acima da linha ideal indica atraso no cronograma.

## Contato

Para questões relacionadas a este projeto, entre em contato com a equipe Crush4Pets através do GitHub.

---

© 2025 Crush4Pets
