# Documento de Requisitos do Sistema de Gerenciamento de Projetos (SGP) - Etapa Final

Este documento detalha os requisitos da terceira e última etapa do Sistema de Gerenciamento de Projetos (SGP), focando na finalização e consolidação das funcionalidades implementadas nas fases anteriores. O objetivo principal desta etapa é garantir que o sistema esteja completamente funcional, otimizado e pronto para uso em ambiente profissional.


## Objetivo

Nesta terceira etapa do desenvolvimento do Sistema de Gerenciamento de Projetos (SGP), o foco será na finalização, otimização e documentação completa do sistema. O objetivo é garantir que o projeto esteja pronto para ser utilizado em um ambiente real, atendendo a todas as boas práticas de desenvolvimento e estando preparado para futuras escalas.


## Estrutura do Projeto 

```
- 📂gerenciamento-projetos
  - 📂backend
    - Container(Docker)
      - Middleware personalizado
      - Autenticação JWT
      - Manipulação de Streams
      - Testes 
  - 📂frontend
    - Container(Docker)
      - Dashboard interativo
      - Integração com APIs de terceiros
      - Filtros e bloqueios baseados em permissões
      
```

## **Tarefas de Consolidação e Completude**

### **Refinamento da Interface de Usuário**

- Descrição: Revisar e aprimorar a interface para garantir que seja intuitiva, responsiva e acessível. **Implementar melhorias visuais e de usabilidade com base em feedback recebido durante as fases anteriores**
- Local: Frontend

### **Otimização do Código**

- Descrição: Realizar uma revisão completa do código para identificar e eliminar redundâncias, melhorar a organização e refatorar trechos que possam ser otimizados. Garantir que todas as funções e métodos sejam bem documentados e seguidos de boas práticas de programação..
- Local: Backend + Frontend

### **Aumento da Segurança**
- Descrição: Implementar criptografia de dados sensíveis no banco de dados. Revisar e reforçar a segurança nas rotas, especialmente aquelas que lidam com dados críticos. Garantir que todas as entradas de usuários sejam validadas e sanitizadas para evitar vulnerabilidades.
- Local: Backend

### **Escalabilidade e Manutenção**
- Descrição: Desenvolvimento de middlewares para manipulação de erros, validação de dados e autenticação. Esses middlewares garantirão uma camada adicional de segurança e controle, interceptando requisições antes de atingirem os endpoints principais.
- Local: Backend

### **Documentação Completa**
- Descrição: Desenvolver uma documentação abrangente do projeto, incluindo guias de instalação, configuração, e uso. Criar um manual do usuário que detalhe como utilizar todas as funcionalidades do sistema.
- Local: Backend + Frontend

## **Entrega/Avaliação** 
Nesta etapa final, o foco principal será avaliar a completude e a qualidade/valor do projeto, além de como você aplicou os conceitos ao longo do desenvolvimento


- Estrutura do Código: Manter a organização e clareza do código, com ênfase na aplicação dos conceitos de Clean Code.
- Cumprimento de Requisitos: Garantir que todas as funcionalidades descritas sejam implementadas conforme especificado e que o projeto esteja totalmente concluído e funcional.
- Lógica de Programação: Soluções eficientes e aplicadas conforme as melhores práticas.
- Metodologia Aplicada: Abordagem estruturada para resolução de problemas e entrega de valor ao produto final. Mostrando um processo de desenvolvimento bem planejado e executado
- Completude do Projeto: Verificar se o projeto está totalmente funcional e atende a todos os requisitos estabelecidos.
- **OBS**: Faça commits claros e descritivos, destacando o progresso e as mudanças realizadas. A avaliação será detalhada e incluirá a verificação de todos os aspectos do projeto, desde a implementação até a finalização.

## Checklist 📝

Abaixo estão as implementações que terão de ser feitas no seu projeto. Quanto mais itens você entregar, melhor será sua avaliação.

---

**Legenda:**

- B -> Backend
- F -> Frontend

---

### Nível 1

|     | Descrição	                                            | Local |
| --- | ------------------------------------------------      | ----- |
| [ ] |	Otimização e melhoria de desempenho do sistema	    |  F B  |
| [ ] | Documentação completa do Projeto    |  F B  |
| [ ] | Implementação de Testes   |  F B  |
| [ ] | Aumento da segurança   |  F B  |
| [ ] | Escabilidade e Manutenibilidade   |  F B  |






