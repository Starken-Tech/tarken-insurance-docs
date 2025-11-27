# 5. E-mail (Templates)

A seção de **E-mail** da plataforma Starken Insurance é focada no gerenciamento de **templates de e-mail**, que são modelos de comunicação padronizados para serem usados em conjunto com as automações. Esta funcionalidade garante consistência na comunicação com corretores e segurados, além de agilizar o envio de notificações importantes.

#### Estrutura da Página

A interface permite criar, visualizar e gerenciar todos os templates de e-mail disponíveis.

* **Barra de Ferramentas:**
  * **Novo template:** Botão para criar um novo modelo de e-mail.
  * **Filtrar e Ordenar:** Ferramentas para organizar e encontrar templates específicos.

#### Tabela de Templates

A lista de templates é organizada em uma tabela que destaca as informações essenciais:

| Coluna        | Descrição                                                                     |
| ------------- | ----------------------------------------------------------------------------- |
| **Template**  | O nome ou código do modelo de e-mail.                                         |
| **Descrição** | Um resumo da finalidade do template e em que contexto ele deve ser utilizado. |
| **Produtos**  | Ícones que indicam a quais produtos de seguro o template está associado.      |
| **Ação**      | Botões para editar, visualizar ou excluir o template.                         |

#### Exemplos de Templates de E-mail

O sistema vem com uma variedade de templates pré-configurados para cobrir as principais etapas do ciclo de vida de uma cotação:

* **Solicitação de Informações:**
  * `013 - PENDENCIA DE INFORMAÇÕES`: Para notificar o corretor sobre dados faltantes.
  * `LEMBRETE DE PRAZO DE RETORNO`: Para alertar sobre o vencimento do prazo para envio de informações.
* **Confirmação e Prazos:**
  * `CONFIRMAÇÃO DE RECEBIMENTO DO QAR`: Para confirmar que o questionário foi recebido.
  * `003 - LINK PARA PREENCHIMENTO EXPIRADO`: Para informar que o prazo de preenchimento do QAR se esgotou.
* **Propostas e Assinaturas:**
  * `020 - ENVIAR PROPOSTA {{SEGURADORA}}`: Para notificar o corretor sobre a chegada de uma nova proposta.
  * `005 - LINK PARA ASSINATURA DIGITAL`: Para enviar o link de assinatura eletrônica de documentos.
* **Pagamentos e Alertas:**
  * `014 - LEMBRETE VENCIMENTO PRIMEIRA PARCELA`: Para lembrar sobre o vencimento da primeira parcela e evitar o cancelamento da apólice.

#### Recursos Avançados

Os templates de e-mail suportam o uso de **variáveis dinâmicas** (ex: `{{SEGURADORA}}`, `{{RAMO}}`), que são substituídas automaticamente pelas informações corretas da cotação no momento do envio. Isso permite um alto grau de personalização e relevância em cada comunicação, mesmo quando enviada de forma totalmente automatizada.
