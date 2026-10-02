# Ração com Razão — GitHub Pages

Site da campanha universitária da UFSC Blumenau, desenvolvida na disciplina de Gestão de Projetos, com a meta de arrecadar 50 kg de ração para cães.

Este pacote contém as páginas prontas para publicação. Não contém contatos, respostas do formulário, planilhas privadas, senhas ou arquivos do servidor. A meta ilustrativa continua identificada no site como uma prévia, não como doações confirmadas.

## Publicar pela primeira vez

1. Entre na sua conta do GitHub e crie um repositório **público** chamado exatamente **racao-com-razao**. Marque a opção para adicionar um README.
2. Extraia o ZIP no computador. Não envie o ZIP fechado.
3. No repositório, clique em **Add file → Upload files**.
4. Arraste a pasta **docs** inteira para o espaço de envio. Ela precisa aparecer como `docs/index.html`, `docs/participar/index.html`, etc. Inclua também este README, substituindo o inicial.
5. Confirme o envio em **Commit changes**, diretamente na branch **main**.
6. Abra **Settings → Pages**. Em **Source**, selecione **Deploy from a branch**. Em **Branch**, selecione **main** e a pasta **/docs**. Clique em **Save**.
7. Aguarde a publicação. O GitHub mostrará o endereço: `https://SEU-USUARIO.github.io/racao-com-razao/`.
8. Teste Início, Participar, Quem recebe e Sobre o projeto. Depois gere o QR Code para esse endereço.

Os caminhos foram preparados para o nome `racao-com-razao`. Se quiser outro nome de repositório ou usar um domínio próprio, peça a adaptação antes de publicar.

O arquivo `docs/.nojekyll` deve permanecer no pacote: ele permite servir a pasta `_next` com os arquivos do visual e das animações.

## Cadastros e revisão

O botão de cadastro abre o mesmo Google Forms. As respostas continuam chegando à planilha privada da equipe. Não publique essa planilha nem coloque os contatos no repositório.

Você revisa as respostas manualmente. Um nome só deve entrar na lista de doadores após confirmação da doação, autorização para divulgar o nome e sua aprovação. Uma mensagem exige autorização e aprovação próprias. Sem autorização para o nome, uma mensagem aprovada pode aparecer como anônima.

## Atualizar depois

1. Envie no chat apenas os conteúdos que autorizou publicar e as mudanças desejadas. Não precisa enviar os contatos.
2. Peça uma atualização da **versão do GitHub Pages**, informando o link do repositório. A versão hospedada originalmente em Sites é independente e não atualiza o GitHub sozinha.
3. Receba o pacote atualizado e envie os arquivos indicados ao mesmo repositório, em **Add file → Upload files**. Confirme em **Commit changes**.
4. O GitHub Pages publica os arquivos novos mantendo o mesmo endereço e o mesmo QR Code.

Para mudanças simples, use apenas os arquivos indicados no pacote de atualização. Evite copiar a pasta do projeto original, `.git`, `.env`, `node_modules`, fontes de servidor ou arquivos da planilha.

## Referência

[Guia oficial de publicação do GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
