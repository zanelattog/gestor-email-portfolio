<div align="center">

# Gestor de E-mails Local

**Da planilha ao acompanhamento de cada conversa.**

Um aplicativo que desenvolvi com apoio de IA e uso na minha rotina de prospecção comercial.

macOS · Intel e Apple Silicon · Organização de contatos · E-mails personalizados

</div>

![Visão geral do aplicativo com dados ilustrativos](imagens/dashboard.png)

> O aplicativo já é usado por mim. Para mostrar como ele funciona sem expor clientes, preparei uma versão de apresentação com empresas A, B e C e dados fictícios. Os números dos prints são exemplos, não resultados comerciais. Nessa versão, os envios estão desativados.

## Por que fiz

Eu precisava organizar as empresas que encontrava, preparar uma abordagem para cada contato e acompanhar o que acontecia depois do envio. Fazer isso entre planilhas, caixa de e-mail e anotações acabava deixando tudo espalhado.

Fui construindo o aplicativo a partir dessa necessidade. Ele reúne a base de contatos, os modelos de mensagem, as campanhas e o histórico em um lugar só. Já faz parte do meu trabalho; este repositório serve para apresentar o projeto.

## Como funciona na prática

**1. Organizo a base.** Importo uma planilha e separo os contatos por empresa, cidade, segmento e departamento. Posso revisar os dados, identificar pendências e marcar quem não deve receber contato.

**2. Completo o que está faltando.** Quando não há e-mail, posso iniciar uma pesquisa automática. O aplicativo procura no site informado e, quando necessário, em fontes públicas de busca. Compara informações da empresa, prioriza endereços ligados ao domínio e registra a origem e o nível de confiança. Quando a evidência não é suficiente, apresenta possibilidades para revisão.

**3. Priorizo as oportunidades.** O sistema pode calcular uma pontuação com critérios como segmento, departamento, porte e disponibilidade de contato. Para uma oferta de piso industrial, por exemplo, isso ajuda a organizar uma base com indústrias e centros logísticos e revisar áreas como manutenção, engenharia, facilities e compras. A pontuação orienta a análise; a escolha de quem abordar continua sendo minha.

**4. Preparo e reviso a mensagem.** Os modelos usam os dados do contato para personalizar o conteúdo. Consigo conferir a prévia, a assinatura e os anexos antes de iniciar uma campanha.

**5. Acompanho cada envio e retorno.** As mensagens são enviadas individualmente, com fila, intervalos e limites configuráveis. O histórico reúne o andamento, as falhas e os retornos, com recursos para acompanhar respostas via IMAP quando configurado.

## Um pouco da interface

### Contatos organizados

![Base de contatos com empresas A, B, C e D e endereços de exemplo](imagens/contacts.png)

*Base ilustrativa: empresas e endereços fictícios, usada apenas para mostrar a organização dos contatos.*

### Campanhas e acompanhamento

![Tela de campanhas com uma campanha ilustrativa](imagens/campaigns.png)

*Uma visão da campanha, do andamento das mensagens e dos controles disponíveis. Os registros desta imagem são simulados.*

## O que fui colocando no aplicativo

| Recurso | Para que uso |
| --- | --- |
| Importação de planilhas e organização em bases | Separar listas e manter o contexto de cada contato. |
| Busca de e-mails ausentes | Reduzir a pesquisa manual, com origem e confiança para revisão. |
| Segmentos, departamentos e pontuação | Organizar a abordagem de acordo com o tipo de empresa e a oferta. |
| Verificação de domínio e tratamento de falhas | Identificar problemas de entrega e revisar os casos que exigem atenção. |
| Modelos, prévia, assinatura e anexos | Preparar mensagens personalizadas antes do envio. |
| Fila, pausas e limites | Controlar o ritmo das campanhas e acompanhar cada mensagem. |
| Histórico e respostas | Retomar conversas e acompanhar oportunidades comerciais. |
| Lista de não enviar e descadastro | Respeitar bloqueios e solicitações para não receber novas mensagens. |
| Painel e relatórios | Consultar o andamento da operação e exportar relatórios. |
| Backup portátil | Transferir dados entre instalações, sem incluir as senhas de e-mail. |

## Onde a IA entra

Esse projeto representa bem o jeito que gosto de trabalhar: eu trago o problema do dia a dia, uso a IA como apoio para desenvolver e melhorar o aplicativo e testo o que foi feito no meu fluxo de trabalho.

É uma construção híbrida. Uso a IA como ferramenta, enquanto continuo responsável pelas decisões, pela revisão e pelo uso do sistema. As rotinas de pesquisa e organização do aplicativo combinam automação e regras; não dependem de um agente decidindo tudo sozinho.

Ainda tenho coisas para melhorar na aparência. Minha prioridade foi fazer algo útil, que me ajudasse a organizar a prospecção e acompanhar as conversas de venda.

## Dados e uso responsável

O fluxo parte de uma base cuja origem e possibilidade de uso precisam ser verificadas. Um dado estar público, ou pertencer a um contato profissional, não significa que possa ser usado sem avaliar finalidade, base legal e direitos da pessoa. Os controles do aplicativo ajudam na operação, mas não certificam a conformidade de uma lista.

Neste portfólio, todos os dados das imagens são fictícios. O código-fonte, as credenciais, os backups e o histórico real ficam privados. A versão de apresentação não envia e-mails nem consulta serviços externos.

Na versão de uso, os dados são armazenados no computador; buscas e conexões de e-mail utilizam serviços externos quando acionadas. Encontrar um endereço não comprova autorização de contato, e um envio aceito pelo servidor não garante leitura ou venda.

Referências: [LGPD](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) e [orientação da ANPD sobre legítimo interesse](https://www.gov.br/anpd/pt-br/assuntos/noticias/anpd-lanca-guia-orientativo-sobre-legitimo-interesse).

---

**Gabriel · [Meu GitHub](https://github.com/zanelattog)**

Este repositório apresenta o projeto e suas telas. Não distribui o código do aplicativo.
