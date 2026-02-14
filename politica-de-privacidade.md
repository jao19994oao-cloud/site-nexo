# Política de Privacidade - NEXO

Última atualização: 14 de fevereiro de 2026

Esta Política de Privacidade explica como o NEXO coleta, usa, compartilha e protege dados pessoais no contexto de operação de funis de atendimento, leads, vendas, análises e mensageria (por exemplo, WhatsApp, Instagram e Messenger), bem como o uso de integrações de pagamento/licenciamento.

## 1. Quem somos (Controlador)

Controlador: NEXO SISTEMA - 64.701.364 JOAO VITOR TEIXEIRA NEVES

CNPJ/CPF: 64.701.364/0001-81

E-mail de contato: CONTATO@NEXO.API.BR

Site/URL: https://nexo.api.br

Quando o NEXO for usado por empresas clientes (multi-tenant), em muitos cenários o "Cliente" (empresa contratante) será o Controlador dos dados de seus leads/contatos e o NEXO atuará como Operador. Ainda assim, esta política descreve as práticas do NEXO enquanto plataforma.

## 2. A quem esta política se aplica

Esta política se aplica a:

- Usuários autenticados do NEXO (operadores/atendentes, administradores e demais usuários autorizados).
- Contatos/leads que interagem com a empresa usuária do NEXO por canais de mensageria integrados (por exemplo, WhatsApp/Instagram/Messenger) e cujas mensagens e dados sejam tratados dentro do NEXO.
- Pessoas que enviem dados para fluxos específicos, como submissão de biometria (documentos e selfie) para análise de venda.

## 3. Quais dados pessoais tratamos

Os tipos de dados podem variar conforme os módulos habilitados, permissões e uso do sistema. Exemplos:

### 3.1. Dados cadastrais e de conta (usuários do sistema)

- Nome, e-mail, credenciais de acesso (hash/senha), perfil/função e permissões.
- Identificadores internos (id de usuário, id de cliente/tenant) e configurações.

### 3.2. Dados de leads/contatos (atendimento, pré-venda e vendas)

- Identificação: nome, documento (por exemplo, CPF), data de nascimento, nome da mãe.
- Contato: telefone, WhatsApp, e-mail.
- Endereço: CEP, rua, número, bairro, cidade, estado, complemento.
- Observações e informações inseridas pelos usuários autorizados.
- Histórico de status/andamento (ex.: rascunho, análise, aprovado, recusado, desistido).

### 3.3. Mensagens e metadados de conversas (canais sociais)

- Conteúdo de mensagens (ex.: texto) enviadas/recebidas por canais integrados.
- Identificadores de plataforma (ex.: id do contato no WhatsApp/Instagram/Messenger) e id de mensagens.
- Nome exibido no perfil do contato (quando fornecido pela plataforma).
- Data/hora de envio/recebimento, fila/atribuição, etiquetas e eventos de atendimento.

### 3.4. Dados financeiros e de comissões (quando aplicável)

- Informações relacionadas a vendas, comissões, repasses e configurações financeiras do cliente (empresa).
- Dados de cobrança/licenciamento do sistema e eventos de pagamento/regularização (por exemplo, via webhooks).

### 3.5. Dados sensíveis (LGPD) - biometria e documentos (quando aplicável)

Se habilitado, o NEXO pode tratar dados sensíveis para finalidade de validação/análise, como:

- Imagens de documento (frente/verso) e selfie.
- Registro de aceite de LGPD e endereço IP no momento do envio.

## 4. Como coletamos os dados

Coletamos dados por meio de:

- Informações fornecidas diretamente por usuários autorizados (cadastros e atualizações).
- Integrações e webhooks de plataformas de mensageria (por exemplo, Meta WhatsApp Cloud API; e, dependendo da configuração, provedores como Gupshup).
- Integrações financeiras/licenciamento (por exemplo, webhooks de pagamento).
- Registros técnicos gerados pelo uso do sistema (logs de auditoria, data/hora, identificadores de operação).

## 5. Finalidades e bases legais (LGPD)

Tratamos dados pessoais para as seguintes finalidades (exemplos) e respectivas bases legais, conforme a LGPD:

- Execução de contrato e procedimentos preliminares: fornecer acesso ao NEXO, operar módulos (leads, vendas, atendimento), suporte e manutenção.
- Legítimo interesse: segurança, prevenção a fraude/abuso, auditoria, melhoria do sistema e garantia de disponibilidade, respeitando direitos e expectativas dos titulares.
- Cumprimento de obrigação legal/regulatória: quando exigido (ex.: registros fiscais/contábeis, atendimento a demandas de autoridades).
- Consentimento: quando necessário, especialmente para dados sensíveis (por exemplo, biometria/documentos) e/ou para finalidades específicas.

Observação: a base legal aplicável pode variar conforme o papel do NEXO (Controlador ou Operador) e a configuração/uso do cliente (empresa usuária).

## 6. Compartilhamento de dados (operadores e terceiros)

Podemos compartilhar dados com:

- Provedores de infraestrutura (hospedagem/servidores, bancos de dados, armazenamento).
- Provedores de mensageria e redes sociais integradas (por exemplo, Meta; e/ou Gupshup, conforme configuração).
- Provedores de pagamento/licenciamento (por exemplo, Asaas), quando aplicável.
- Prestadores de serviço essenciais (monitoramento, segurança, suporte técnico), sob obrigações contratuais de confidencialidade.

Não vendemos dados pessoais.

## 7. Transferências internacionais

Alguns provedores podem processar dados fora do Brasil (ex.: plataformas globais de mensageria). Nesses casos, adotamos mecanismos e garantias exigidos pela LGPD, conforme aplicável.

## 8. Retenção e descarte

Mantemos dados pessoais pelo tempo necessário para:

- Cumprir as finalidades descritas nesta política.
- Cumprir obrigações legais/regulatórias.
- Exercer direitos em processos administrativos/judiciais/arbitrais.

Prazos podem variar por tipo de dado e pelo contrato com o cliente. Quando aplicável, dados podem ser anonimizados ou excluídos de forma segura.

## 9. Segurança da informação

Adotamos medidas técnicas e administrativas razoáveis para proteger dados pessoais, como:

- Controle de acesso por permissões (RBAC) e segregação por cliente/tenant.
- Mascaramento de dados e restrições para visualização de informações sensíveis, conforme permissões.
- Logs de auditoria para ações críticas (ex.: revelação temporária de dados sensíveis, quando habilitado).
- Proteção de segredos (chaves, tokens) via variáveis de ambiente e boas práticas de gestão.

Nenhum sistema é 100% seguro. Se identificarmos incidente relevante, adotaremos medidas de contenção e comunicação conforme a legislação aplicável.

## 10. Direitos dos titulares

Nos termos da LGPD, o titular pode solicitar, conforme aplicável:

- Confirmação de existência de tratamento.
- Acesso, correção e atualização.
- Anonimização, bloqueio ou eliminação.
- Portabilidade, quando aplicável.
- Informações sobre compartilhamento.
- Revogação de consentimento, quando o tratamento se basear em consentimento.

Para solicitar, utilize o canal: CONTATO@NEXO.API.BR.

Importante: quando o NEXO atuar como Operador para uma empresa cliente, podemos direcionar a solicitação ao Controlador (empresa) e/ou auxiliar conforme contrato.

## 11. Cookies e tecnologias de rastreamento

O NEXO pode utilizar cookies e armazenamento local estritamente necessários para autenticação e funcionamento da aplicação web.

## 12. Conteúdos de terceiros e links

O NEXO pode integrar com serviços de terceiros. As práticas desses terceiros são regidas por suas políticas. Recomendamos consultar as políticas de privacidade aplicáveis (por exemplo, das plataformas de mensageria).

## 13. Alterações desta política

Podemos atualizar esta política periodicamente. Publicaremos a versão atualizada e ajustaremos a data de "Última atualização".

## 14. Contato

Dúvidas ou solicitações:

- Canal de privacidade: CONTATO@NEXO.API.BR
- Site: https://nexo.api.br

