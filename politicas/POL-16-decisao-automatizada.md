# Política de Decisões Automatizadas — SERRACRED

| Campo | Informação |
|---|---|
| política | Decisões automatizadas com explicabilidade e canal de revisão |
| versao | 1.0 |
| fonte_da_obrigacao | legal (Lei nº 13.709/2018 - LGPD, art. 20, caput e §§ 1º e 2º) |
| obrigacao | Assegurar ao titular informação clara sobre os critérios de decisões tomadas unicamente por tratamento automatizado e um canal para solicitar a revisão dessas decisões. |
| responsável | Encarregado pelo Tratamento de Dados Pessoais |
| aprovador | Diretoria Executiva |
| evidência_de_cumprimento | Registro de decisões automatizadas com ficha de critérios por sistema; registro de pedidos de revisão (protocolo, prazos, revisor, conferência do revisor com a ficha, recusa parcial, justificativa e data da comunicação ao Encarregado, resultado); relatório anual de validação assinado pelo responsável do sistema e pelo Encarregado |
| periodicidade_de_revisão | semestral |

## 1. Objetivo

Garantir que toda decisão tomada unicamente com base em tratamento automatizado de dados pessoais, e que afete interesses do titular, seja identificada, explicável em linguagem clara e passível de revisão a pedido do titular, cumprindo o art. 20 da LGPD.

## 2. A quem se aplica

A todas as áreas e sistemas da SERRACRED que tomem ou apoiem decisões sobre cooperados, como score e limite de crédito, pré-aprovação, crédito rural, perfil de investidor na plataforma de investimentos e acesso a serviços, incluindo sistemas operados pelo centro de processamento do sistema cooperativo e por outros terceiros.

## 3. Regras

### 3.1 Registro dos sistemas

Todo sistema que tome decisão sobre cooperado sem intervenção humana deve constar do registro de decisões automatizadas antes de entrar em produção. A ficha do sistema deve ser aprovada pelo Encarregado, pelo Diretor Financeiro (Riscos) quando envolver crédito, e pelo Gerente de Tecnologia da Informação. Sistema fora do registro não pode ser colocado em produção.

### 3.2 Ficha de critérios

Cada sistema registrado deve ter uma ficha com: finalidade da decisão; dados pessoais usados; critérios e lógica da decisão descritos em linguagem não técnica; área e cargo responsáveis; data da última validação.

### 3.3 Informação ao titular

No momento em que a decisão for comunicada, o titular deve ser informado de que ela foi automatizada e de como solicitar revisão (canal e prazo).

### 3.4 Canal de revisão

O canal de revisão deve estar publicado no site e ser gratuito. Cada pedido recebe número de protocolo em até 1 dia útil.

### 3.5 Análise do pedido

O pedido de revisão deve ser analisado por pessoa natural com competência para manter ou alterar a decisão, que não conste na lista de responsáveis da ficha do sistema (regra 3.2), e respondido por escrito, com fundamentação, em até 15 dias corridos. O registro do pedido deve ter um campo em que o Encarregado confirma que o revisor não consta nessa lista.

### 3.6 Segredo comercial e industrial

Ao explicar os critérios, a SERRACRED pode proteger segredo comercial e industrial, mas não pode negar a explicação geral dos critérios e procedimentos. Toda recusa parcial deve ser registrada no pedido de revisão, com os campos: recusa parcial (sim/não), justificativa escrita e data da comunicação ao Encarregado, que deve ocorrer em até 2 dias úteis..

### 3.7 Validação anual

Cada sistema deve ser validado uma vez por ano, conforme o procedimento abaixo:

a) Amostra: no mínimo 400 decisões do período, sorteadas aleatoriamente, ou todas as decisões, se forem menos de 400.
b) Comparação: calcular a taxa de resultado favorável (por exemplo, crédito aprovado) para cada grupo de titulares definido na ficha do sistema.
c) Limite: se a taxa de qualquer grupo for inferior a 80% da taxa do grupo com maior resultado favorável, o resultado é considerado potencialmente discriminatório.
d) Consequência: o responsável do sistema deve apresentar plano de correção em até 30 dias, e o sistema deve ser suspenso se a correção não for concluída em 90 dias.

O relatório deve ser assinado pelo responsável do sistema e pelo Encarregado, e arquivado no repositório.

### 3.8 Mudança de critérios

Mudança nos critérios de decisão só entra em produção depois de a ficha do sistema ser atualizada por Pull Request aprovado pelo Encarregado.

## 4. Como o cumprimento é verificado

O cumprimento é verificado por:

- **Registro de decisões automatizadas:** cada sistema em produção tem ficha vigente, e o histórico do repositório mostra autor, data e aprovação de cada alteração.
- **Registro de pedidos de revisão:** protocolo, data de recebimento, data da resposta, revisor, conferência do revisor com a ficha, recusa parcial e resultado. O Encarregado acompanha mensalmente o percentual de respostas dentro de 15 dias.
- **Relatórios anuais de validação** de cada sistema, com a assinatura do responsável do sistema e a do Encarregado.
- **Amostragem semestral da auditoria interna**, independente do Encarregado: sorteio de decisões comunicadas, para conferir o aviso da regra 3.3, e sorteio de pedidos de revisão, para conferir o prazo de 15 dias, a independência do revisor e o registro das recusas parciais. A auditoria interna também recalcula o percentual de respostas no prazo.

Não servem como evidência: declaração de que "o canal existe" sem registro de pedidos, ficha de sistema sem histórico de versões, ou ata de reunião que apenas cite a política.
