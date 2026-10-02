# Prompt de consulta RAG limitada — Caso simulado CA-2026-014

> **Aviso:** as fontes selecionadas e qualquer resposta gerada neste fluxo são fictícias e servem exclusivamente ao estudo de caso.

## Fontes autorizadas

Use **somente** os dois arquivos abaixo como base da resposta:

1. `apoio/fonte_1.md` — *Guia fictício de acessibilidade em processos seletivos*.
2. `apoio/fonte_2.md` — *Protocolo fictício de análise responsável de relatos*.

Não use conhecimento externo, páginas da internet, leis, normas, documentos do caso ou fontes não listadas. Não invente fatos, referências, obrigações ou detalhes que não estejam expressos nas duas fontes autorizadas.

## Prompt

```text
Você está respondendo a uma consulta sobre o caso fictício CA-2026-014.

Pergunta: [INSIRA_AQUI_A_PERGUNTA]

Use exclusivamente estas fontes autorizadas:
- apoio/fonte_1.md — Guia fictício de acessibilidade em processos seletivos.
- apoio/fonte_2.md — Protocolo fictício de análise responsável de relatos.

Regras obrigatórias:
1. Responda somente com informações sustentadas pelas fontes autorizadas.
2. Para cada afirmação relevante, informe o arquivo de origem e reproduza um trecho curto que comprove a afirmação.
3. Use a citação no formato: [arquivo: `caminho/do/arquivo.md` | trecho: “...”].
4. Se a pergunta não puder ser respondida pelas fontes, escreva: “Informação insuficiente nas fontes selecionadas.” Explique brevemente o que elas permitem afirmar, sem preencher lacunas com suposições.
5. Não trate as fontes como referências reais, legais ou institucionais. Mencione, quando necessário, que são fictícias e didáticas.
6. Não apresente conclusão definitiva sobre discriminação, responsabilidade individual ou obrigação legal.
7. Não mencione nem utilize arquivos que não estejam na lista de fontes autorizadas.

Estruture a resposta assim:

Resposta:
[resposta objetiva]

Evidências nas fontes selecionadas:
- [arquivo: `...` | trecho: “...”]
- [arquivo: `...` | trecho: “...”]

Limite da resposta:
[incerteza, limitação ou declaração de informação insuficiente, quando aplicável]
```

## Exemplo de uso fictício

**Pergunta:** Como a solicitação de acessibilidade deve ser tratada no cenário?

**Resposta esperada:** A solicitação deve ser tratada como um ajuste operacional, com registro restrito e atendimento antes da entrevista. [arquivo: `apoio/fonte_1.md` | trecho: “a solicitação seja recebida sem exigir justificativas além do necessário para viabilizar o recurso, registrada de maneira restrita e atendida antes da entrevista.”]

**Limite da resposta:** As fontes são fictícias e não estabelecem obrigação legal real.
