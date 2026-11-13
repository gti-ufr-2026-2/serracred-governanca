---
politica: Classificação da informação e tratamento por nível
versao: 1.0
fonte_da_obrigacao: normativa (ABNT NBR ISO/IEC 27002:2022, controles de classificação e rotulagem da informação)
obrigacao: informações classificadas em público, interno, restrito ou sigiloso, rotuladas, e tratadas conforme o nível
responsavel: Gerente de Segurança da Informação
aprovador: Diretor Executivo
evidencia_de_cumprimento: inventário de ativos de informação com nível atribuído e ata de revisão anual da classificação
periodicidade_de_revisao: anual
---

# Classificação da informação

## 1. Objetivo
Definir os níveis de classificação da informação e o tratamento obrigatório de cada um, para que a proteção, o compartilhamento e a contratação de terceiros sejam proporcionais ao risco.

## 2. A quem se aplica
A todos os colaboradores, estagiários e terceiros que criam, acessam, armazenam ou transmitem informação da organização, em qualquer meio (digital, papel ou verbal), e a todos os sistemas e fornecedores que a tratam.

## 3. Regras
1. Toda informação recebe um dos quatro níveis: **público**, **interno**, **restrito** ou **sigiloso**.
2. **Público**: pode ser divulgado sem restrição, após aprovação da área de comunicação.
3. **Interno**: uso restrito à organização. Não pode ser enviado a externos sem autorização do gestor da área.
4. **Restrito**: acesso apenas por perfil autorizado, transmissão com criptografia e registro de acesso. Inclui dados pessoais comuns.
5. **Sigiloso**: acesso nominal aprovado pelo proprietário da informação, criptografia em repouso e em trânsito, e proibição de cópia em dispositivo pessoal. Inclui dados pessoais sensíveis e dados estratégicos.
6. O **proprietário da informação** (gestor da área que a produz) atribui o nível no momento da criação ou recebimento. Na dúvida, aplica-se o nível imediatamente superior até a definição.
7. Nenhum sistema ou plataforma que trate informação restrita ou sigilosa pode ser contratado sem que o contrato conste: nível de classificação dos dados, nível de serviço (SLA), cláusula de saída, portabilidade e devolução ou eliminação dos dados. A Área de TI não pode assinar contrato sem essa verificação registrada.
8. Documentos e arquivos restritos e sigilosos levam rótulo visível (cabeçalho, marca d'água ou nome de pasta).
9. O inventário de ativos de informação, com o nível de cada um, é revisto uma vez por ano e sempre que um novo sistema ou fornecedor for incorporado.
10. A reclassificação só é feita pelo proprietário da informação, com registro da data e da justificativa.

## 4. Como o cumprimento é verificado
- O Gerente de Segurança da Informação mantém o inventário com nível, proprietário e data da última revisão.
- Uma amostra trimestral de documentos e sistemas verifica rótulo e controles do nível.
- Cada contratação de fornecedor traz o checklist da regra 7 assinado.
- A revisão anual é registrada em ata e aprovada pelo Diretor Executivo, por Pull Request neste repositório.
