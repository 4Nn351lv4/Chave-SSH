# Chave-SSH
WINDOWS:
git bash
ssh-keygen -t ed25519 -C "emailnogithub"
senha
senha
cd /c/users/"usuário"/.ssh/
ls
cat id_ed25519.pub

Copia o conteúdo e cola no github na aba sobre ssh
Volta no git bash e nesse mesmo local da pasta /.ssh digite
ls
pwd para vr o caminho completo da pasta /.ssh
eval $(ssh-agent -s)
ls
ssh-add id_ed25519
senha

Faça o teste clonando um repositorio pela chave ssh
git clone "..."
yes
ls

---------------------------------------------------------

LINUX: no próprio terminal
ssh-keygen -t ed25519 -C "emailnogithub"
senha
senha
cd /home/usuário/.ssh
ls
cat id_ed25519.pub

Copia o conteúdo e cola no github na aba sobre ssh
Volta no terminal e nesse mesmo local da pasta /.ssh digite
eval $(ssh-agent -s)
ssh-add id25519
senha

Faça o teste clonando um repositorio pela chave ssh
git clone "..."
yes
ls


