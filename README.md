# Personal Finance AI Manager

Este projeto implementa um agente de inteligência artificial especializado em gestão financeira pessoal, desenvolvido para operar com rigor técnico, foco em economia e eficiência.  
O sistema foi concebido para o contexto brasileiro, considerando Selic, CDI, IPCA, IOF e CET em todas as análises.

---

## Arquitetura

O agente foi construído sobre um LLM (Large Language Model), utilizando técnicas avançadas de prompt engineering para estruturar regras de negócio, formatos de saída e metodologias de análise.

Princípios de design:

- Precisão absoluta: não aceita médias ou arredondamentos, apenas valores exatos.  
- Economia como métrica central: cada corte ou renegociação é quantificado em impacto mensal e anual.  
- Contexto Brasil: todos os cálculos consideram indicadores nacionais.  

---

## Metodologia de Trabalho

O fluxo operacional segue uma lógica determinística:

1. Checagem inicial – coleta e validação de dados (receitas, despesas, dívidas, investimentos, metas).  
2. Mapeamento do mês – consolidação em tabelas de fluxo de caixa e cronogramas semanais.  
3. Cortes de custos – mínimo de três táticas por categoria, com impacto estimado.  
4. Gestão de dívidas – métodos avalanche (maior taxa) ou bola de neve (menor saldo), incluindo simulações de portabilidade e antecipação.  
5. Reserva de emergência – meta definida em meses de despesas essenciais, priorizando Tesouro Selic e CDBs com liquidez diária.  
6. Investimentos – recomendação apenas após estabilização de dívidas, com carteira simples e diversificada conforme perfil (conservador, moderado, arrojado).  
7. Plano de ação – relatório mensal com 5 prioridades claras, prazos e métricas.  

---

## Padrões de Saída

Os outputs são apresentados em Markdown estruturado, para clareza e aplicabilidade:

### Exemplo de orçamento mensal
```markdown
| Categoria      | Valor (R$) | Observações |
|----------------|------------|-------------|
| Entradas       | 8.500,00   | Salário + renda extra |
| Despesas Fixas | 4.200,00   | Moradia, transporte, saúde |
| Dívidas        | 1.300,00   | Cartão + empréstimo |
| Reserva        | 500,00     | Tesouro Selic |
| Lazer          | 600,00     | Viagem e restaurantes |
```

## Considerações de Design

Transparência: cada recomendação vem acompanhada de justificativa técnica.

Proatividade: cobra dados faltantes e sinaliza inconsistências.

Responsabilidade: não solicita informações sensíveis (como senhas), não promete retornos garantidos e não substitui consultoria profissional.

## Resultado

O resultado é um gestor financeiro virtual pragmático, combinando a flexibilidade de um LLM com metodologia estruturada.
O agente entrega ao usuário relatórios claros, cortes mensuráveis e planos de ação aplicáveis, funcionando como um guia disciplinado de gestão financeira pessoal.

## Roadmap Futuro

 Integração com dashboards visuais.

 Exportação em CSV/Excel.

 Versão em app móvel.

 Integração com APIs de mercado financeiro.

 
---

```markdown
Acesse a solução:
[https://chatgpt.com/g/g-68b995c7d0848191b4fd8c34236bddea-guardiao-do-bolso?model=gpt-5](https://chatgpt.com/g/g-68b995c7d0848191b4fd8c34236bddea-guardiao-do-bolso)
```
