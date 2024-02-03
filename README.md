## Requisitos Funcionais

### Aluno:

- Cadastrar Aluno
- Editar Dados do Aluno
- Recuperar Senha do Aluno
- Cancelar Conta do Aluno
- Gerar Certificado Apos Aluno Concluir o curso

### Aluno - Nota de Cursos:

- Adicionar Curso na Grade do Aluno
- Cancelar ou Remover Curso da Grade do Aluno
- Visualizar Progresso do Curso do Aluno

### Instrutor:

- Instrutor de Cadastramento
- Editar Dados do Instrutor
- Recuperar Senha do Instrutor
- Cancelar Conta do Instrutor

### Instrutor - Cursos e Aulas:

- Cadastrar Curso e Aula
- Atualizar Aulas e Cursos
- Excluir Curso
- Organizar Cursos por Categoria

### Mecanismo de Busca de Cursos:

- Buscar Curso por Nome
- Buscar Curso por Categoria
- Buscar Curso por Nome do Instrutor

### Notificações:

- Sistema deve Enviar Notificações para Alunos sobre Novos Cursos

### Caderno de Anotações:

- Sistema deve Ter Caderno de Anotações do Aluno

### Aluno-Instrutor de Comunicação:

- Aluno pode enviar perguntas para o instrutor
- Listar Perguntas e Visualizar Mensagens do Instrutor
- Instrutor Pode Visualizar Mensagens do Aluno
- Instrutor pode enviar respostas para os alunos

### Login e Acesso à Área do Aluno:

- Aluno realizar login se estiver cadastrado no sistema
- Aluno não pode acessar a área do aluno se não tiver logado
- A página principal é bloqueada caso o usuário não esteja logado; se ele tentar acessar pela URL via GET enviar mensagem de alerta de erro 

## Requisitos Não Funcionais

- Controle de dados em memória (cache)
- Envio de serviços de email em background ou assíncrono, rodar o serviço em um thread
- Respostas do servidor: mínimo 10s, máximo 30s de tempo de resposta
- Tratamento de erros do servidor e do cliente
- Gerenciamento e configurações do pool de conexões
- Tempo de resposta máximo de 2s
- Máximo de conexões: 30
- Mínimo de conexões que não estão sendo usadas: 10
- Limitar o tamanho do upload para vídeo e imagem
- Manter a segurança do sistema através do mecanismo de segurança contra fraudes e acesso indevido

## Observações

- Futuramente, considere a possibilidade de adicionar módulos ou funcionalidades adicionais.
- Certificar-se de implementar uma estrutura organizada para os cursos, com categorias bem definidas.
- Implementar um sistema robusto de notificações para manter os alunos informados sobre novos cursos.
- O sistema deve ocultar componentes da tela dependendo da permissão do usuário.
