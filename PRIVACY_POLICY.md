# Política de Privacidade - EverChat Extension

**Última atualização:** 26 de novembro de 2025
**Versão:** 1.5.0
**Desenvolvedor:** Evertec

---

## 1. Introdução

A Evertec respeita sua privacidade e está comprometida em proteger seus dados pessoais. Esta Política de Privacidade descreve como a extensão EverChat ("Extensão", "nós", "nosso") coleta, usa, armazena e protege suas informações quando você utiliza nossa extensão de navegador.

Ao instalar e usar o EverChat Extension, você concorda com os termos desta Política de Privacidade. Se você não concordar com qualquer parte desta política, não utilize a extensão.

---

## 2. Informações que Coletamos

### 2.1. Dados de Configuração

Coletamos e armazenamos localmente as seguintes informações de configuração:

- **URL da API de IA**: O endereço da API de inteligência artificial que você configura
- **Chaves de API e Tokens de Autenticação**: Credenciais necessárias para acessar a API de IA
- **Headers HTTP Personalizados**: Cabeçalhos HTTP configurados para autenticação e comunicação com a API
- **Endpoints Configurados**: Lista de endpoints de IA que você adiciona e personaliza
- **Mensagens de Sistema**: Instruções personalizadas para os modelos de IA
- **Preferências de Interface**: Tema (claro/escuro), idioma, configurações de aparência

**Armazenamento:** Todos esses dados são armazenados **localmente no seu navegador** usando `chrome.storage.sync` e `chrome.storage.local`. Nenhum desses dados é enviado para servidores da Evertec.

### 2.2. Histórico de Conversas

A extensão pode armazenar localmente:

- **Mensagens enviadas**: Perguntas e comandos que você envia para a IA
- **Respostas recebidas**: Respostas fornecidas pela API de IA
- **Timestamps**: Data e hora das conversas

**Armazenamento:** O histórico é armazenado **localmente no seu navegador**. Você pode limpar o histórico a qualquer momento através das configurações da extensão.

**Nota:** Por padrão, o histórico completo de conversas pode ser desabilitado para economizar espaço de armazenamento.

### 2.3. Contexto da Página Web

Quando você utiliza a extensão, ela extrai informações da página web atual:

- **Título da página**: O título exibido na aba do navegador
- **URL da página**: O endereço completo da página que você está visualizando
- **Conteúdo textual**: Texto visível na página (parágrafos, títulos, listas)
- **Estrutura da página**: Cabeçalhos, listas e tabelas (quando relevante)
- **Metadados**: Descrição, palavras-chave e autor (quando disponíveis)

**Uso:** Essas informações são extraídas **somente quando você abre o popup da extensão** e são enviadas à API de IA que você configurou para fornecer respostas contextualizadas.

**Importante:** A extração de contexto ocorre apenas na aba ativa e somente quando solicitado por você. Não monitoramos nem armazenamos seu histórico de navegação.

### 2.4. Dados de Telemetria e Logs

Para melhorar a qualidade e desempenho da extensão, coletamos dados de telemetria:

- **Email do usuário**: Obtido através da conta Google conectada ao navegador Chrome
- **ID de Sessão**: Identificador único gerado diariamente para agrupar eventos
- **Eventos de Uso**: Ações realizadas na extensão (abertura do popup, chamadas à API, erros)
- **Informações Técnicas**: Versão da extensão, navegador, sistema operacional
- **Métricas de Desempenho**: Tempo de resposta das APIs, taxa de sucesso/erro das requisições
- **Mensagens de Erro**: Detalhes de erros técnicos para diagnóstico

**Finalidade:** Esses dados são usados exclusivamente para:
- Análise de uso e desempenho da extensão
- Identificação e correção de bugs
- Melhoria da experiência do usuário
- Suporte técnico

**Armazenamento:** Os dados de telemetria são enviados para o sistema interno de logs da Evertec (EverLog) hospedado em servidores corporativos seguros.

---

## 3. Como Usamos Suas Informações

### 3.1. Funcionalidade Principal

Usamos suas informações para:

- **Conectar-se à API de IA**: Usar suas credenciais e configurações para fazer chamadas à API
- **Enviar contexto à IA**: Transmitir informações da página para obter respostas relevantes
- **Exibir respostas**: Mostrar as respostas da IA formatadas no popup
- **Manter preferências**: Lembrar suas configurações entre sessões
- **Sincronizar configurações**: Permitir que suas configurações sejam sincronizadas entre dispositivos (via Chrome Sync)

### 3.2. Melhoria do Serviço

Usamos dados de telemetria para:

- Identificar e corrigir bugs técnicos
- Analisar padrões de uso para melhorar funcionalidades
- Medir desempenho e latência das APIs
- Desenvolver novos recursos baseados em necessidades reais dos usuários

### 3.3. Suporte Técnico

Em caso de problemas técnicos, podemos usar logs e dados de telemetria para:

- Diagnosticar problemas reportados
- Fornecer assistência personalizada
- Reproduzir e corrigir erros

---

## 4. Compartilhamento de Informações

### 4.1. Com APIs de Terceiros

Quando você usa a extensão, compartilhamos informações com:

**API de IA Configurada por Você:**
- Enviamos suas mensagens e o contexto da página para a API de IA que você configurou (ex: Claude, OpenAI, Groq, APIs corporativas)
- As políticas de privacidade desses provedores se aplicam aos dados que eles recebem
- Você é responsável por escolher provedores confiáveis e revisar suas políticas de privacidade

**Responsabilidade:** A Evertec não controla como as APIs de terceiros usam, armazenam ou processam seus dados. Recomendamos revisar as políticas de privacidade dos provedores de IA que você escolher.

### 4.2. Dentro da Evertec

Dados de telemetria coletados são compartilhados internamente apenas com:

- **Equipe de Desenvolvimento**: Para análise técnica e melhoria da extensão
- **Equipe de Suporte**: Para resolução de problemas reportados
- **Equipe de Segurança**: Para monitoramento de segurança e detecção de ameaças

**Acesso Restrito:** Apenas funcionários autorizados têm acesso aos dados de telemetria, e somente para as finalidades descritas acima.

### 4.3. Sem Venda de Dados

**Nunca vendemos, alugamos ou comercializamos seus dados pessoais para terceiros.**

### 4.4. Exigências Legais

Podemos divulgar suas informações se exigido por lei, ordem judicial, processo legal ou solicitação governamental válida.

---

## 5. Armazenamento e Segurança dos Dados

### 5.1. Armazenamento Local

A maioria dos seus dados é armazenada **localmente no seu navegador**:

- **chrome.storage.sync**: Configurações sincronizadas entre dispositivos (criptografadas pelo Chrome)
- **chrome.storage.local**: Dados locais do dispositivo (histórico, cache)

**Controle Total:** Você tem controle total sobre esses dados e pode excluí-los a qualquer momento através das configurações da extensão ou do navegador.

### 5.2. Segurança

Implementamos medidas de segurança para proteger seus dados:

- **Sanitização de Entrada**: Prevenção contra ataques XSS (Cross-Site Scripting)
- **Validação de Origem**: Verificação de mensagens para prevenir cross-extension attacks
- **Permissões Mínimas**: Solicitamos apenas as permissões necessárias
- **Manifest V3**: Usamos a versão mais recente e segura do Chrome Extensions
- **HTTPS**: Todas as comunicações com APIs usam conexões criptografadas
- **Criptografia em Trânsito**: Dados sincronizados via Chrome Sync são criptografados

### 5.3. Retenção de Dados

- **Configurações e Preferências**: Mantidas até você desinstalar a extensão ou limpar manualmente
- **Histórico de Conversas**: Mantido localmente até você limpar através da extensão
- **Logs de Telemetria**: Retidos por até 12 meses nos servidores da Evertec para análise

---

## 6. Seus Direitos e Controles

### 6.1. Acesso e Controle

Você tem os seguintes direitos sobre seus dados:

- **Visualizar Dados**: Acessar suas configurações e histórico através da interface da extensão
- **Exportar Configurações**: Baixar suas configurações em formato JSON
- **Importar Configurações**: Restaurar configurações de um backup
- **Limpar Histórico**: Apagar o histórico de conversas a qualquer momento
- **Desabilitar Telemetria**: Desativar coleta de logs (pode afetar suporte técnico)

### 6.2. Exclusão de Dados

Para excluir seus dados:

1. **Limpar Histórico**: Use o botão "Limpar Histórico" na extensão
2. **Resetar Configurações**: Exporte suas configurações antes de desinstalar
3. **Desinstalar Extensão**: Remove todos os dados locais do navegador
4. **Solicitar Exclusão de Logs**: Entre em contato conosco para solicitar exclusão de logs de telemetria

### 6.3. Sincronização de Dados

Você pode desabilitar a sincronização de configurações:

- Desative o Chrome Sync nas configurações do navegador
- As configurações ficarão apenas no dispositivo local

---

## 7. Cookies e Tecnologias de Rastreamento

**Esta extensão NÃO usa cookies ou tecnologias de rastreamento de terceiros.**

Não instalamos, modificamos ou acessamos cookies de sites que você visita.

---

## 8. Privacidade de Crianças

Esta extensão não é destinada a crianças menores de 13 anos. Não coletamos intencionalmente dados de crianças. Se você acredita que coletamos dados de uma criança inadvertidamente, entre em contato conosco imediatamente.

---

## 9. Mudanças nesta Política de Privacidade

Podemos atualizar esta Política de Privacidade periodicamente. Quando fizermos alterações:

- Atualizaremos a data de "Última atualização" no topo deste documento
- Notificaremos você através de um aviso na extensão (para mudanças significativas)
- Publicaremos a nova política no repositório oficial da extensão

**Recomendação:** Revise esta política periodicamente para se manter informado sobre como protegemos seus dados.

---

## 10. Conformidade Legal

### 10.1. LGPD (Lei Geral de Proteção de Dados - Brasil)

Esta extensão está em conformidade com a LGPD:

- **Base Legal**: Consentimento do usuário ao instalar a extensão
- **Finalidade Legítima**: Processamento de dados apenas para funcionalidades descritas
- **Transparência**: Informações claras sobre coleta e uso de dados
- **Segurança**: Medidas técnicas para proteção de dados
- **Direitos do Titular**: Acesso, correção, exclusão e portabilidade de dados

### 10.2. GDPR (Europa)

Para usuários na União Europeia:

- **Controlador de Dados**: Evertec
- **Propósito do Processamento**: Fornecimento de serviços da extensão
- **Base Legal**: Consentimento do usuário
- **Direitos GDPR**: Acesso, retificação, exclusão, portabilidade, restrição de processamento

---

## 11. Contato

Para questões sobre privacidade, exercer seus direitos ou reportar preocupações:

**Evertec - Equipe de Privacidade**

- **Email de Suporte**: [INSERIR EMAIL DE SUPORTE]
- **Email DPO (Data Protection Officer)**: [INSERIR EMAIL DO DPO]
- **Repositório GitHub**: [INSERIR LINK DO REPOSITÓRIO]
- **Portal de Suporte**: [INSERIR LINK DO PORTAL]

**Tempo de Resposta:** Nos comprometemos a responder solicitações relacionadas à privacidade em até 5 dias úteis.

---

## 12. Informações Adicionais

### 12.1. Código Aberto

O código-fonte da extensão pode estar disponível para revisão, permitindo que você:
- Audite como seus dados são processados
- Verifique as práticas de segurança implementadas
- Contribua com melhorias

### 12.2. Transparência

Estamos comprometidos com transparência total sobre:
- Que dados coletamos
- Como usamos seus dados
- Com quem compartilhamos (apenas APIs que você configura)
- Como protegemos seus dados

### 12.3. Sem Rastreamento entre Sites

Esta extensão:
- Não rastreia sua navegação em outros sites
- Não cria perfis de comportamento
- Não vende dados para anunciantes
- Não injeta anúncios em páginas

---

## 13. Glossário

- **API**: Interface de Programação de Aplicações - permite comunicação com serviços de IA
- **Chrome Sync**: Serviço do Google Chrome que sincroniza dados entre dispositivos
- **Contexto da Página**: Informações extraídas da página web atual para enviar à IA
- **EverLog**: Sistema interno de logging da Evertec para telemetria
- **Manifest V3**: Versão mais recente da especificação de extensões do Chrome
- **Storage Local**: Armazenamento de dados no navegador do usuário
- **Telemetria**: Coleta automática de dados de uso para análise e melhoria do produto
- **XSS**: Cross-Site Scripting - tipo de vulnerabilidade de segurança web

---

## 14. Histórico de Versões

| Versão | Data | Mudanças |
|--------|------|----------|
| 1.5.0 | 26/11/2025 | Política de Privacidade inicial |

---

## 15. Aceitação

Ao instalar e usar o EverChat Extension, você reconhece que leu, entendeu e concorda com esta Política de Privacidade.

Se você não concordar com esta política, não instale ou desinstale a extensão imediatamente.

---

**Evertec © 2025 - Todos os direitos reservados**

*Esta política de privacidade foi elaborada com transparência e compromisso com a proteção de dados dos nossos usuários.*
