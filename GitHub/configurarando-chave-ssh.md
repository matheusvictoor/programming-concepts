# Solução para o erro de autenticação no git após a remoção do suporte à autenticação por senha pelo GitHub

Existem algumas maneiras de evitar ter que inserir seu nome de usuário e senha toda vez que você faz um commit no git, uma dela é **Usar SSH**.
 
A configuração do SSH para usar com o git pode ser um pouco complexa, mas é uma boa opção para evitar digitar seu nome de usuário e senha toda vez que você fizer um commit. Aqui estão os passos gerais para configurar o SSH com o git:

 **1** - Gerar chaves SSH: Primeiro, você precisará gerar uma chave SSH em seu computador. Isso pode ser feito usando o comando ssh-keygen. Certifique-se de escolher um local para salvar sua chave e fornecer uma senha para protegê-la.
    
   - Gerar chaves SSH é um processo simples e pode ser feito usando o comando ssh-keygen no terminal ou prompt de comando. Aqui estão os passos detalhados:

   - Abrir o terminal ou prompt de comando: Primeiro, você precisará abrir o terminal ou prompt de comando em seu computador. Isso pode ser feito pressionando as teclas Windows + R e digitando "cmd" ou "powershell" no Windows ou abrindo o terminal no Linux ou MacOS.

   - Gerar a chave: Em seguida, você pode gerar sua chave SSH usando o comando **`ssh-keygen`**. Isso irá iniciar o processo de geração da chave, e você será solicitado a escolher um local para salvar a chave e fornecer uma senha para protegê-la.

   - Forneça o caminho: Quando solicitado, você deve fornecer o caminho onde você deseja salvar a chave, ou pressionar enter para salvar no local padrão.

   - Forneça uma senha: Em seguida, você será solicitado a fornecer uma senha para proteger a chave. Isso é opcional, mas altamente recomendado para garantir a segurança da chave.

   - Verifique se a chave foi gerada: Depois de concluir o processo, você pode verificar se a chave foi gerada verificando o local onde você salvou a chave. Ela terá dois arquivos, geralmente com extensão .pub e .pem

   - Adicione a chave pública: Copie o conteúdo do arquivo com extensão .pub e adicione-o ao seu serviço de hospedagem de repositório, como GitHub, GitLab, etc.
    
    
 **2** - Adicionar chave SSH ao serviço de hospedagem: Em seguida, você precisará adicionar sua chave SSH ao seu serviço de hospedagem de repositório, como GitHub, GitLab, etc. Isso geralmente pode ser feito adicionando a chave publica gerada no passo 1 no perfil do usuário em sua conta.
 Adicionar uma chave SSH ao GitHub é um processo simples e pode ser feito através da interface web do GitHub. Aqui estão os passos detalhados:

- Acesse o GitHub: Primeiro, você precisará acessar o GitHub e fazer login na sua conta.

- Acesse as configurações: Em seguida, clique no seu avatar no canto superior direito e selecione **"Settings"** (ou Configurações).

- Acesse as SSH e GPG keys: Na página de configurações, selecione **"SSH and GPG keys"** (ou Chaves SSH e GPG) no menu à esquerda.

- Adicione uma nova chave: Clique no botão "New SSH key" (ou Nova chave SSH) e forneça um título para a chave e cole o conteúdo da chave pública gerada no passo anterior.

- Adicione a chave: Clique em **"Add SSH key"** (ou Adicionar chave SSH) para adicionar a chave ao GitHub.
    
**3** - Configurar o git para usar SSH: Depois de adicionar sua chave ao serviço de hospedagem, você precisará configurar o git para usar SSH em vez de HTTPS. Isso pode ser feito usando o comando **`git config --global url."git@github.com:".insteadOf "https://github.com/"`** (substituindo "github.com" pelo seu serviço de hospedagem).
    
 **4** - Testando a conexão: Por fim, você pode testar sua conexão SSH com o git usando o comando **`ssh -T git@github.com (substituindo "github.com"`** pelo seu serviço de hospedagem). Se tudo estiver configurado corretamente, você deve ver uma mensagem de boas-vindas do serviço de hos pedagem.
 
**Espero ter te ajudado!**
