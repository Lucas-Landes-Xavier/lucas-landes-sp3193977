
# Ficha de Entrega — Trabalho Final LP1

## 1. Identificação do aluno

**Nome do aluno:** Lucas Landes Xavier Martins

**Prontuário completo:** SP3193977

**Turma:** 213-B

**Data da entrega:** 21/11/2026

## 2. Informações da publicação

**URL estável de produção:**  
https://lucas-martins-sp3193977.vercel.app

**URL de login:**  
https://lucas-martins-sp3193977.vercel.app/login

**URL do repositório:**  
https://github.com/Lucas-Landes-Xavier/lucas-landes-sp3193977

**Commit/versão avaliada:**  
`99960ed` — Corrige configuracao Flask na Vercel.

## 3. Contas de avaliação

**Conta administrativa exclusiva do professor (e-mail):**  
celsoadministrador@email.com

**Conta de operador para testes (e-mail):**  
celsooperador@email.com

**Canal privado utilizado para entregar as senhas:**  
Arquivo PDF denominado `senha_contas.pdf`, enviado juntamente com a ficha de entrega pelo Moodle, em atividade com acesso restrito ao professor.

**Observação:** As senhas não estão incluídas neste documento, pois serão fornecidas separadamente. Também não são compartilhados a `SECRET_KEY`, as credenciais do Neon ou os tokens de acesso às plataformas.

## 4. Checklist de validação

- [x] URL contém meu nome e prontuário completo.
- [x] Login é do supermercado; não exige conta Vercel do professor.
- [x] Banco PostgreSQL individual e migração aplicados.
- [x] Conta do professor funciona.
- [x] Operador, caixa, venda e pagamentos simulados testados.
- [x] Estoque, compras, financeiro, gráfico, Excel e ticket testados.
- [x] Os dois temas estão disponíveis.
- [x] Persistência confirmada após Redeploy.
- [x] Testes automatizados executados; resultado registrado abaixo.
- [x] `.env` e bancos locais não foram enviados ao repositório.

## 5. Resultado dos testes

Foram executados **20 testes automatizados utilizando pytest**, todos aprovados, sem falhas, em 16,08 segundos.

Também foram realizados testes manuais de autenticação, vendas simuladas, emissão de comprovantes, atualização de estoque, registro de compras, movimentações financeiras, fechamento de caixa, visualização de gráficos e exportação Excel.

A persistência dos dados foi confirmada após uma nova implantação na Vercel.

## 6. Limitações e problemas conhecidos

Não foram identificadas falhas durante os testes realizados, incluindo as verificações manuais e os testes automatizados.

O sistema possui finalidade exclusivamente acadêmica, sendo as operações de vendas, compras e movimentações financeiras simuladas, sem integração com instituições bancárias, processamento de pagamentos reais ou emissão de documentos fiscais.

A recuperação automática de senha por e-mail depende da configuração de um serviço SMTP, não realizada nesta implantação. Entretanto, permanece disponível a alternativa administrativa de geração de links de recuperação pelo terminal, conforme previsto na documentação do projeto.

## 7. Alterações pessoais realizadas pelo aluno

Foram realizadas a configuração do ambiente local, a integração da aplicação com o banco de dados PostgreSQL hospedado no Neon e a publicação do sistema Flask na Vercel, utilizando o repositório GitHub.

Também foram ajustadas as dependências do projeto para compatibilidade com a versão do Python utilizada e corrigida a configuração do arquivo `vercel.json` para permitir a implantação.

Por fim, foi configurado o domínio individual conforme o padrão solicitado pelo professor.
