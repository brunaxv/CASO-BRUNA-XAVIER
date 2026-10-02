# Prompt de auditoria e segunda revisão — Caso simulado CA-2026-014

> **Aviso:** o prompt, a resposta de auditoria e a decisão descritos neste documento são fictícios e didáticos. Não constituem parecer, investigação ou decisão real.

## 1. Prompt de auditoria

```text
Você atua como auditor independente de um estudo de caso fictício. Revise os documentos abaixo para verificar coerência, limites da evidência, proteção de informações e presença de revisão humana:

- apoio/caso_sanitizado.md
- apoio/fonte_1.md
- apoio/fonte_2.md
- evidencias/resposta_inicial.md
- evidencias/verificacao.md
- evidencias/auditoria.md
- evidencias/revisao_humana.md
- docs/limites_e_sigilo.md

Regras obrigatórias:
1. Considere todos os conteúdos fictícios; não use fontes externas nem trate o caso como ocorrência real.
2. Não consulte nem reproduza dados do arquivo entrada/relato_bruto.md.
3. Diferencie: fato documentado, alegação, informação pendente e inferência.
4. Identifique inconsistências, lacunas, riscos de privacidade, vieses ou conclusões além da evidência disponível.
5. Para cada achado, indique o arquivo e um trecho curto que o sustente.
6. Não determine responsabilidade individual, não conclua que houve discriminação e não formule orientação jurídica.
7. Registre se a revisão humana é necessária e quais informações faltam para uma conclusão mais segura.

Entregue a resposta com as seções: Escopo auditado; Achados; Pontos positivos; Lacunas e riscos; Recomendação de encaminhamento; Limites da auditoria.
```

## 2. Resposta da segunda conversa ou tarefa — simulada

### Escopo auditado

Foi realizada uma segunda leitura independente dos documentos autorizados no prompt. A leitura foi limitada à versão sanitizada e aos registros de análise, sem acesso ao relato bruto fictício.

### Achados

| Achado | Classificação | Evidência |
| --- | --- | --- |
| O pedido de acessibilidade é tratado como parte relevante da cronologia, mas não como prova isolada da causa da eliminação. | Coerente | `evidencias/verificacao.md`: “não permitem afirmar a causa da eliminação”. |
| A comunicação de encerramento não apresenta critérios detalhados. | Lacuna documental | `apoio/caso_sanitizado.md`: “sem apresentação dos critérios detalhados de avaliação”. |
| A análise registra a necessidade de evitar conclusão automática. | Controle positivo | `evidencias/auditoria.md`: “Ausência de decisão exclusivamente automatizada.” |
| A versão para consulta reduz exposição de informações pessoais. | Controle positivo | `apoio/caso_sanitizado.md`: “remove ou generaliza identificadores e dados de saúde”. |
| Não há rubrica completa, evidência técnica da plataforma ou contexto integral da fala relatada. | Limitação crítica | `evidencias/auditoria.md`: “qualquer conclusão definitiva seria inadequada”. |

### Pontos positivos

O conjunto documental mantém a separação entre alegação, verificação e decisão. Há explicitação do caráter fictício das fontes, registro de limites e previsão de revisão humana. A sanitização permite consulta do cenário sem expor identificadores simulados desnecessários.

### Lacunas e riscos

A falta de critérios completos de seleção impede avaliar a justificativa técnica apresentada. A fala atribuída ao recrutador não possui contexto integral. Portanto, seria inadequado transformar indícios em conclusão definitiva ou atribuir responsabilidade individual.

### Recomendação de encaminhamento

Manter a classificação como inconclusiva quanto à causa da eliminação. Registrar a necessidade de aperfeiçoar a documentação dos critérios de seleção, a comunicação sobre acessibilidade e a preservação de registros relevantes. Submeter o resultado a decisão humana responsável.

### Limites da auditoria

Esta resposta é uma segunda análise simulada, baseada apenas nos arquivos indicados e em fontes fictícias. Ela não confirma fatos externos, não substitui investigação e não produz decisão automática.

## 3. Decisão humana sobre os achados — simulada

**Responsável fictícia:** Carolina Mendes, Coordenação do Núcleo de Integridade Simulado  
**Data fictícia:** 24 de setembro de 2026

Após examinar os achados da segunda revisão, a responsável humana decide:

1. **Aceitar** os achados sobre insuficiência de evidências para determinar a causa da eliminação.
2. **Manter** a classificação do caso como inconclusiva, sem atribuição de responsabilidade individual.
3. **Registrar** indício de oportunidade de melhoria no tratamento de solicitações de acessibilidade e na documentação dos critérios de seleção.
4. **Determinar**, para fins deste estudo, que qualquer nova conclusão dependa de documentação complementar fictícia e nova revisão humana.

## Fundamentação da decisão humana

A decisão considera que há consistência entre a cronologia relatada e os documentos de verificação, mas faltam elementos essenciais para estabelecer nexo causal. A responsável humana também confirma que o uso de IA, quando houver, permanece apenas como suporte de organização e análise, nos limites definidos em `docs/limites_e_sigilo.md`.

## Registro final

A decisão foi tomada por revisão humana simulada e não por resultado automático. Ela se aplica somente ao estudo de caso fictício CA-2026-014.
