# relatorios-virtualbox


1️⃣ Abrir o PowerShell

Clique no Menu Iniciar → digite PowerShell → abra.

2️⃣ Navegar para a pasta onde quer criar o arquivo

Exemplo: usar a pasta Documentos:

cd $HOME\Documents 

3️⃣ Criar o arquivo com o conteúdo do relatório

Use o comando abaixo para criar o arquivo relatorio-winxp.md já com seu conteúdo. Copie e cole tudo no PowerShell:

@"


DENTRO DESSE CODIGO COLOQUE SEU RELATÓRIO REFERENTE A MÁQUINA VIRTUAL QUE VOCE CRIOU



"@ > relatorio-winxp.md


Esse comando cria o arquivo relatorio-winxp.md com todo o conteúdo do seu relatório.

4️⃣ Clonar o repositório (caso ainda não tenha feito)


git clone https://github.com/yanlt32/relatorios-virtualbox.git


cd relatorios-virtualbox

5️⃣ Mover o relatório para o repositório


move $HOME\Documents\relatorio-winxp.md .


O . indica que o arquivo vai para a pasta atual do repositório.

6️⃣ Adicionar o arquivo ao Git


git add relatorio-winxp.md

7️⃣ Fazer o commit


git commit -m "Adiciona relatório de instalação do Windows XP"

8️⃣ Enviar para o GitHub
git push origin main


Se o branch principal do seu repositório for master, use git push origin master.
