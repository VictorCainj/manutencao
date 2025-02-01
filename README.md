#Tutorial: Sistema de Anotações de Contratos

Introdução
Este sistema foi desenvolvido para ajudar na gestão de contratos, permitindo a criação, agendamento, edição e exclusão de anotações. Ele também possui funcionalidades de busca e filtros para facilitar a organização dos contratos.

Estrutura do Sistema
O sistema é dividido em várias seções, cada uma com um propósito específico:

Loader: Carregamento da página
Login Modal: Modal de login
Main Layout: Layout principal com controle de usuário e anotações
Modals de Criação e Detalhes: Modais para criar e visualizar detalhes de anotações e agendamentos
Área de Notificações: Exibe notificações de sucesso, alerta e erro
Dashboard: Exibe estatísticas das anotações
Notas e Paginação: Exibe a lista de anotações com paginação
Acesso e Login
Ao acessar o sistema, o usuário será direcionado para o modal de login:

E-mail: Digite seu e-mail (ex.: manutencao@madia.com.br)
Senha: Digite sua senha (ex.: password123)
Clique no botão Entrar para fazer login.
Após o login com sucesso, o modal de login será ocultado e o layout principal será exibido.

Layout Principal
Logo e Informações do Usuário
Logo: Exibe a logo da empresa.
Informações do Usuário: Exibe o e-mail do usuário logado e um ícone de usuário.
Controle Principal
Criar Anotação: Clique para abrir o modal de criação de anotação.
Criar Agendamento: Clique para abrir o modal de criação de agendamento.
Importar Contratos: Clique para importar contratos de um arquivo JSON.
Baixar Todos os Contratos: Clique para baixar todos os contratos em um arquivo JSON.
Logout: Clique para sair do sistema.
Área de Notificações
Notificações: Exibe mensagens de sucesso, alerta e erro.
Dashboard
Estatísticas: Exibe um gráfico de barras com a quantidade de chamados por status (Abertos, Fechados, Em Agendamento, Verificados Hoje, Cláusula Especial).
Busca e Filtros
Busca: Digite para pesquisar contratos por número, locador, locatário ou endereço.
Filtros de Data e Status:
Data: Filtre por contratos mais recentes ou mais antigos.
Status: Filtre por todos os chamados, abertos, em agendamento, verificados hoje, fechados ou cláusula especial.
Módulo: Filtre por todos os módulos, criação, análise, negociação, execução ou finalização.
Lista de Notas e Paginação
Notas: Exibe a lista de anotações de contratos.
Paginação: Navegue entre as páginas de anotações.
Modals de Criação e Detalhes
Criar Anotação
Clique no botão "Criar Anotação" para abrir o modal.
Preencha os campos obrigatórios:
Número de Contrato
Locador
Locatário
Endereço
Problema
Módulo
Clique em "Salvar" para criar a anotação. Caso contrário, clique em "Cancelar".
Criar Agendamento
Clique no botão "Criar Agendamento" para abrir o modal.
Pesquise e selecione um contrato existente.
Preencha os campos obrigatórios:
Nome do Prestador
Data do Agendamento
Descrição do Agendamento
Clique em "Salvar" para criar o agendamento. Caso contrário, clique em "Cancelar".
Detalhes da Anotação
Clique em uma anotação na lista para abrir o modal de detalhes.
Visualize as informações do contrato:
Número de Contrato
Locador
Locatário
Problema
Endereço
Status
Prestador (se agendado)
Data do Agendamento (se agendado)
Descrição do Agendamento (se agendado)
Comentários
Ações Disponíveis:
Copiar Comentários: Copie os comentários do contrato.
Baixar Contrato: Baixe os detalhes do contrato em um arquivo de texto.
Cancelar Agendamento: Cancele o agendamento e altere o status para aberto.
Excluir: Exclua a anotação.
Finalizar: Finalize a anotação.
Reabrir: Reabra uma anotação finalizada.
Transformar em Cláusula Especial: Transforme a anotação em uma cláusula especial.
Adicionar Comentário: Adicione um comentário à anotação.
Editar Comentário: Edite um comentário existente.
Excluir Comentário: Exclua um comentário existente.
Adicionar Subcomentário: Adicione um subcomentário a um comentário existente.
Importar e Exportar Contratos
Importar Contratos
Clique no botão "Importar Contratos".
Selecione um arquivo JSON contendo os contratos.
Os contratos válidos serão importados e exibidos na lista de anotações.
Exportar Contratos
Clique no botão "Baixar Todos os Contratos".
Um arquivo JSON contendo todos os contratos será baixado.
Notificações
O sistema exibe notificações para informar sobre ações realizadas:

Sucesso: Ação realizada com sucesso.
Alerta: Informações importantes ou avisos.
Erro: Erros que ocorreram durante a execução de uma ação.
Logout
Clique no botão "Logout".
O usuário será deslogado e redirecionado para o modal de login.
Conclusão
Este sistema foi desenvolvido para facilitar a gestão de contratos, proporcionando uma interface intuitiva e funcionalidades úteis para criar, agendar, editar e excluir anotações. Utilize este tutorial para explorar todas as funcionalidades e otimizar a gestão dos seus contratos.
