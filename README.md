# Relatório de Impacto à Proteção de Dados Pessoais (RIPD)

## 1. Identificação da Organização
- **Nome da Organização**: Lanchonete Nuget
- **Endereço**: Av. Paulista, 1106 / Edifício Paulista, 1100
- **Responsável pelo Tratamento dos Dados**: Ronaldinho Gaúcho, Gerente de TI
- **DPO (Encarregado de Dados)**: Mário Jorge Lobo Zagallo, Consultor de Proteção de Dados

## 2. Descrição do Tratamento de Dados Pessoais
- **Objetivo do Tratamento**: Implementar um sistema de autoatendimento para melhorar a eficiência e a qualidade do serviço, possibilitando aos clientes realizar pedidos, pagamentos e acompanhar o status de seus pedidos de forma autônoma. Os dados coletados são usados para gerenciar o processo de pedidos e para campanhas de marketing.
- **Tipo de Dados Coletados**: Nome, e-mail, CPF, histórico de pedidos, preferências de produtos, dados de pagamento via QRCode (intermediado pelo Mercado Pago).
- **Titulares dos Dados**: Clientes da lanchonete que utilizam o sistema de autoatendimento.
- **Bases Legais para o Tratamento**:
  - **Consentimento**: Para o cadastro voluntário dos clientes com nome, e-mail e CPF.
  - **Execução de Contrato**: Para processar pedidos e pagamentos.
- **Duração do Tratamento**:
  - **Dados de Identificação**: Mantidos por até 12 meses após o último uso do sistema.
  - **Histórico de Pedidos e Preferências**: Armazenados por até 24 meses para fins de análise e campanhas promocionais.
  - **Dados de Pagamento**: Não são armazenados diretamente no sistema; o Mercado Pago gerencia o processamento.

## 3. Avaliação de Riscos
- **Identificação de Riscos**:
  - **Risco de Vazamento de Dados Pessoais**: Possibilidade de acesso não autorizado aos dados dos clientes.
  - **Risco de Uso Indevido dos Dados**: Dados dos clientes podem ser usados para finalidades não autorizadas, como spam ou venda para terceiros.
  - **Risco de Fraude**: Fraude nas transações de pagamento via QRCode.
- **Probabilidade de Ocorrência**:
  - **Vazamento de Dados**: Médio (devido ao armazenamento digital e ao acesso por múltiplos usuários do sistema).
  - **Uso Indevido dos Dados**: Baixo (implementação de políticas de uso de dados claras e controles de acesso restritos).
  - **Fraude**: Baixo (uso de intermediário confiável como Mercado Pago).
- **Impacto Potencial**:
  - **Vazamento de Dados**: Alto (comprometimento da privacidade e confiança dos clientes).
  - **Uso Indevido dos Dados**: Médio (possível dano à reputação e perda de clientes).
  - **Fraude**: Alto (impacto financeiro e perda de confiança dos clientes).
- **Nível de Risco**:
  - **Vazamento de Dados**: Médio a Alto
  - **Uso Indevido dos Dados**: Baixo a Médio
  - **Fraude**: Médio

## 4. Medidas de Mitigação
- **Medidas Técnicas**:
  - **Criptografia**: Uso de criptografia para proteger dados sensíveis, como CPF e histórico de pedidos.
  - **Autenticação de Usuários**: Implementação de autenticação forte para acesso ao painel administrativo.
  - **Monitoramento de Acessos**: Logs de acesso ao sistema para auditoria e identificação de acessos não autorizados.
- **Medidas Organizacionais**:
  - **Treinamento de Funcionários**: Treinamento regular em segurança da informação e proteção de dados.
  - **Política de Privacidade**: Política de privacidade clara e acessível aos clientes, explicando como os dados serão usados.
  - **Controle de Acesso**: Restrição de acesso ao painel administrativo apenas a funcionários autorizados.
- **Procedimentos de Resposta a Incidentes**:
  - **Plano de Resposta a Incidentes**: Procedimento definido para a resposta rápida em caso de vazamento de dados, incluindo comunicação com os titulares e as autoridades competentes.
  - **Notificação aos Titulares**: Procedimento de notificação imediata aos clientes em caso de violação de dados.

## 5. Conformidade com a LGPD
- **Análise de Conformidade**:
  - **Princípios de Transparência e Finalidade**: Dados são coletados e utilizados apenas para os fins descritos e com o consentimento dos clientes.
  - **Minimização de Dados**: Somente os dados essenciais para o funcionamento do sistema são coletados.
  - **Segurança dos Dados**: Implementação de medidas técnicas e organizacionais adequadas para proteger os dados pessoais.
- **Direitos dos Titulares**:
  - **Acesso e Correção**: Clientes podem acessar e corrigir seus dados através do sistema ou solicitando ao estabelecimento.
  - **Exclusão e Anonimização**: Opção para os clientes solicitarem a exclusão ou anonimização de seus dados.
- **Transferência Internacional de Dados**: Não há transferência internacional de dados, já que todos os dados são processados e armazenados localmente ou por provedores de serviços nacionais.

## 6. Conclusão e Recomendações
- **Resumo dos Resultados**: O sistema de autoatendimento da Lanchonete Nuget apresenta riscos de médio a alto impacto relacionados ao tratamento de dados pessoais, especialmente em termos de segurança e privacidade. No entanto, medidas de mitigação adequadas foram implementadas para minimizar esses riscos.
- **Recomendações**:
  - **Revisão Regular de Segurança**: Realizar auditorias periódicas para garantir a eficácia das medidas de segurança.
  - **Atualização de Políticas**: Atualizar políticas de privacidade e segurança conforme necessário, especialmente com base em feedback dos clientes e mudanças legislativas.
  - **Engajamento com os Clientes**: Promover a transparência e incentivar os clientes a exercerem seus direitos em relação aos seus dados pessoais.
- **Próximas Etapas**:
  - **Monitoramento Contínuo**: Manter um processo contínuo de monitoramento dos riscos e das medidas de mitigação.
  - **Revisão Periódica do RIPD**: Revisar e atualizar este relatório anualmente ou sempre que houver mudanças significativas no sistema.

## 7. Aprovação
- **Responsável pela Aprovação**: Ronaldinho Gaúcho, Gerente de TI
- **Data de Aprovação**: 08/08/2024
