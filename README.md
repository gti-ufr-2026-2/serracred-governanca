# SERRACRED — Registro de riscos e politicas

Repositorio da disciplina **Governanca de Tecnologia da Informacao** — Sistemas de Informacao, UFR, 2026/2.

A SERRACRED e uma cooperativa de credito ficticia usada como organizacao-caso da disciplina.
Aqui nao se escreve codigo: o GitHub e usado como **plataforma de governanca**.

## O mapeamento

| No GitHub | Em governanca |
|---|---|
| Issue | Um risco identificado, com causa, evento e consequencia |
| Labels | Probabilidade, impacto, categoria e estrategia de tratamento |
| Assignee | O dono do risco — sempre um cargo |
| Project | A matriz de probabilidade e impacto |
| Comentario de outra dupla | A segunda linha de defesa desafiando a primeira |
| Pull Request | Prestacao de contas com evidencia: quem aprovou, quando, com que justificativa |
| CODEOWNERS | A alcada: quem tem poder de decisao sobre o que |
| Historico do arquivo | A trilha de auditoria |

## EAD 3 — registro de riscos (prazo 01/10)

1. Aceite o convite da organizacao e **ative a autenticacao de dois fatores**.
2. Abra 3 issues pelo template **Risco de TI**, no formato causa -> evento -> consequencia.
3. Aplique as labels: uma de `prob:`, uma de `impacto:`, uma de `cat:`, a da evidencia (`E1` a `E8`) e a da sua dupla.
4. Adicione cada issue ao Project **Matriz de Riscos SERRACRED**.
5. Comente criticamente em uma issue de **outra** dupla.

## EAD 4 — politica como codigo (prazo 08/10)

1. Reserve um tema no issue fixado.
2. Crie `politicas/POL-<dupla>-<tema>.md` a partir de `politicas/POLITICA-MODELO.md`, em uma branch nova.
3. Abra o Pull Request e responda as quatro perguntas do template.
4. Revise o PR de outra dupla.
5. Tente o merge. **Voce nao vai conseguir** — falta a aprovacao de quem tem alcada. Isso e proposital.

## Como se escreve um risco

**Serve:** "Devido a existencia de link de dados unico e a ausencia de teste de contingencia desde 2021 (causa), o data center pode permanecer indisponivel por periodo prolongado (evento), resultando em interrupcao do atendimento nas 38 agencias e exposicao a sancao regulatoria (consequencia)."

**Nao serve:** "Risco de indisponibilidade do data center." — e categoria, nao risco.
