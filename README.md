# AV Leads · protótipo de interface

Protótipo navegável do AV Leads, o sistema de prospecção e qualificação de empresas da
Aurélia Vitalis. Mostra como o sistema vai ficar antes do desenvolvimento.

**Todos os dados são fictícios.** Empresas, CNPJs, telefones, contratos e valores foram
gerados para demonstração. Nenhuma integração é real e nada é enviado a lugar nenhum.

## O que dá para experimentar

- **Visão geral:** funil do piloto, vidas contratadas e desempenho por segmento, com
  denominador e "sem base" quando não há dados.
- **Empresas:** filtros por cidade, segmento, CNAE principal ou secundário, situação e
  contato. Exportação CSV que remove quem pediu para não ser contatado.
- **Ficha da empresa:** pontuação explicada item a item, qualificação com "não sei"
  diferente de "não", contatos com origem e alerta de telefone compartilhado.
- **Pipeline:** arraste os cartões. Ganho exige vidas, valor e referência do contrato.
- **Agenda:** fila do dia com registro de tentativa ou conversa em dois toques.
- **Importação:** prévia, validação e relatório. Reimportar o mesmo arquivo não duplica nada.
- **Administração:** mexa nos pesos da pontuação e veja a fila reordenar ao vivo.

No celular, a navegação fica na barra de baixo e o foco é o dia a dia: a fila de hoje e o
registro rápido de contato. Atalho no computador: `Ctrl K` (ou `⌘ K`) abre a busca.

A qualificação traz também as perguntas de contexto vindas do benchmark de clientes
(rotatividade, cobertura do benefício atual, convenção coletiva, contador e turnos), o
alerta quando a convenção coletiva exige plano e o cadastro de escritórios contábeis como
parceiros.

Arquivo único, sem dependências além das fontes do Google Fonts. `index.html` é a página
do site; `Prototipo.html` é a mesma página, para enviar como arquivo.
