# Especificação do projeto — Estudo de caso fictício CA-2026-014

> **Status:** material educacional fictício. Todos os fatos, pessoas, organizações, fontes e documentos foram inventados.

## Finalidade

Demonstrar, de forma organizada e segura, o ciclo de tratamento de um relato fictício que envolve pedido de acessibilidade em um processo seletivo: registro do relato, identificação de dados sensíveis, sanitização para consulta, verificação, auditoria, revisão humana e orientação inicial.

O projeto também ilustra limites apropriados para o uso de IA: apoio à organização e à redação, sem substituição de julgamento humano ou conclusão automática.

## Público-alvo

- Estudantes e pessoas em treinamento sobre documentação de casos.
- Pessoas que desejam compreender fluxos de sanitização, rastreabilidade e revisão humana.
- Avaliadores do estudo de caso e colaboradores autorizados a consultar o repositório.

O projeto não se destina a apurar ocorrências reais, orientar decisões jurídicas ou tratar dados pessoais verdadeiros.

## Escopo e limites

O cenário aborda apenas uma situação fictícia de candidatura a estágio, pedido de recurso de acessibilidade e análise documental limitada. O caso não prova discriminação, não atribui responsabilidade e não representa uma empresa, pessoa ou política real.

Para detalhes de confidencialidade, compartilhamento e uso de IA, consultar `docs/limites_e_sigilo.md`.

## Estrutura esperada

| Área | Conteúdo esperado |
| --- | --- |
| `entrada/` | Relato bruto fictício com identificação de dados pessoais e sensíveis simulados |
| `apoio/` | Caso sanitizado e fontes de embasamento explicitamente inventadas |
| `evidencias/` | Resposta inicial, verificação, auditoria e revisão humana |
| `entrega/` | Orientação inicial à pessoa relatora fictícia |
| `docs/` | Especificação, limites, sigilo e orientações de uso |

## Critérios de aceitação

O projeto será considerado completo quando:

1. todos os documentos informarem, quando pertinente, que o conteúdo é fictício;
2. `entrada/relato_bruto.md` apresentar dados pessoais simulados e identificar a informação sensível;
3. `apoio/caso_sanitizado.md` remover ou generalizar identificadores e explicar as transformações aplicadas;
4. `apoio/fonte_1.md` e `apoio/fonte_2.md` trouxerem referências inventadas, diferentes entre si e claramente rotuladas como fictícias;
5. os arquivos em `evidencias/` formarem uma sequência coerente de relato, verificação, auditoria e revisão humana;
6. a revisão humana não apresentar conclusão definitiva sem evidência suficiente;
7. `docs/limites_e_sigilo.md` definir cuidados de compartilhamento, sigilo e uso responsável de IA;
8. o `README.md` orientar uma nova pessoa sobre a finalidade, a navegação e o uso seguro do repositório;
9. a URL do repositório for incluída no campo pendente do `README.md` após sua criação.

## Validação recomendada

Antes da entrega, revisar a coerência entre as datas fictícias, confirmar que nenhum dado real foi incluído e verificar se o README aponta para todos os principais documentos do projeto.
