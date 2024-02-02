# Requisitos Funcionais

## Operações que o Sistema Deve Realizar:


1. **Aluno:**
    - Cadastrar Aluno
    - Editar Dados do Aluno
    - Recuperar Senha do Aluno
    - Cancelar Conta do Aluno
   
    

2. **Aluno - Grade de Cursos:**
    - Adicionar Curso na Grade do Aluno
    - Cancelar ou Remover Curso da Grade do Aluno
    - Visualizar Progresso do Curso do Aluno

3. **Instrutor:**
    - Cadastrar Instrutor
    - Editar Dados do Instrutor
    - Recuperar Senha do Instrutor
    - Cancelar Conta do Instrutor

4. **Instrutor - Cursos e Aulas:**
    - Cadastrar Curso e Aula
    - Atualizar Aulas e Curso
    - Deletar Curso
    - Organizar Cursos por Categoria
    - Mecanismo de Busca de Cursos:
        - Buscar Curso por Nome
        - Buscar Curso por Categoria
        - Buscar Curso por Nome do Instrutor

5. **Notificações:**
    - Sistema deve Enviar Notificações para Alunos sobre Novos Cursos

6. **Caderno de Anotações:**
    - Sistema deve Ter Caderno de Anotações do Aluno

7. **Comunicação Aluno-Instrutor:**
    - Aluno Pode Enviar Perguntas para o Instrutor
    - Listar Perguntas e Visualizar Mensagens do Instrutor
    - Instrutor Pode Visualizar Mensagens do Aluno
    - Instrutor Pode Enviar Respostas para os Alunos

8.  ** -aluno relizar login se estiver cadastrado no sistema **
9.  ** -aluno so pode acessar a area do aluno estando logado **
10. ** -a pagina  principal e bloqueada caso o usuario que nao esta logado tente acessalo pela URL via get **
   

# Requisitos Não Funcionais

- Controle de dados em memória (cache)
- Envio de serviços de email em background ou assíncrono, rodar o serviço em uma thread
- Respostas do servidor: mínimo 10s, máximo 30s de tempo de resposta
- Tratamento de erros do servidor e do cliente
- Gerenciamento e configurações do pool de conexões
- Tempo de resposta máximo de 2s
- Máximo de conexões: 30
- Mínimo de conexões que não estão sendo usadas: 10
- limitar o tamnho de uplod para video  e imagem
- manter a segurança do sistema atraves de mencanismo de segurança fraudes acesso indevido 


## Observação:
- Futuramente, considerar a possibilidade de adicionar módulos ou funcionalidades adicionais.
- Certificar-se de implementar uma estrutura organizada para os cursos, com categorias bem definidas.
- Implementar um sistema robusto de notificações para manter os alunos informados sobre novos cursos.
- O sistema deve esconder componentes da tela dependendo da permissão do usuário.
