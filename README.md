# sistemas_operacionais
Repositório da matéria Sistemas Operacionais.  
CENTRO DE ENSINO UNIFICADO DE BRASÍLIA - UniCEUB
FACULDADE DE TECNOLOGIA E CIÊNCIAS SOCIAIS APLICADAS
CURSO DE CIÊNCIA DA COMPUTAÇÃO
DISCIPLINA SISTEMAS OPERACIONAIS

DOCUMENTAÇÃO DE COMO INSTALAR E INICIAR O CEUB-OS EM
UMA MÁQUINA VIRTUAL NO VIRTUAL BOX.

Autor:
Gustavo Gomes de Jesus

Brasília, DF (2020)

APRESENTAÇÃO

No semestre de 2020 o Professor Aderbal Botelho lecionador da disciplina
Sistemas Operacionais propôs a ideia de criarmos uma distribuição Linux, com o
objetivo de colocarmos em prática todos os conhecimentos adquiridos em sala.
O projeto deu início no dia 26 de agosto de 2020, com isso houve a
separação dos grupos, e com base nessa separação ocorreu os surgimentos das
equipes: Core (Desenvolvimento), Visual e aparência, Ux e divulgação.
Logo após o surgimento das equipes ocorreu a votação para o nome da
distribuição Linux, e a partir dessa votação veio o nome CEUB OS.
Antes de começarmos precisamos saber o que é um Sistema Operacional, o
que é uma máquina virtual e o porquê de utilizarmos o VirtualBox.
O que é um Sistema operacional ? O sistema operacional ou SO é o
software principal que gerencia todo o hardware e software de um computador.
Além disso, ele também é responsável pelo gerenciamentos da memória e todos os
processos do computador. Ele também permite que você se “comunique” com o seu
computador sem saber o “idioma do computador”. Dessa forma, podemos concluir
que sem um sistema operacional, um computador é inútil.
Escolhemos o Sistema Operacional Linux pois ele é o mais utilizado no
mundo, e é um Sistema operacional com código fonte aberto, por esse motivo ele
oferece a oportunidade de outras pessoas personalizar ou até mesmo criar novas
distribuições a partir dele.
O CEUB-OS foi criado com o objetivo de auxiliar os alunos do UniCEUB,
fornecendo programas específicos voltado para a área acadêmica, e vale ressaltar
que é um sistema leve e com isso acaba rodando bem em qualquer máquina.
O que é uma máquina virtual ? Uma máquina virtual é um software de
ambiente computacional em que um sistema operacional ou programa pode ser
instalado e executado. De maneira mais simplificada, podemos dizer que a máquina
virtual funciona como um “computador dentro de outro computador”.
Porque iremos utilizar o VirtualBox ? O VirtualBox é um software open
source, aplicativo gratuito, multi-plataforma para criar, gerenciar e executar
máquinas virtuais (VMs) - computadores cujos componentes de hardware são
emulados pelo computador host, o computador que executa o programa. VirtualBox
pode ser executado em Windows, Mac OS X, Linux e Solaris.
OBJETIVO
O objetivo dessa documentação é auxiliar pessoas que se interessaram em
baixar e instalar o CEUB-OS em uma Máquina Virtual. O usuário instalando o
CEUB-OS na máquina virtual terá a mesma experiência de um usuário que instalou
no Sistema operacional host. A instalação não é complexa, só seguir os manuais e
instruções abaixo

MANUAIS E INSTRUÇÕES

INSTALAÇÃO DO VIRTUALBOX
Antes de começar a seguir os passos de instalação e inicialização do
CEUB-OS, precisamos baixar e instalar o VirtualBox. Após a instalação do
VirtualBox siga os passos.
Link para o download do VirtualBox:https://www.virtualbox.org/
Após entrar no site, clique em “Download VirtualBox.
 Imagem 01: Site de download do virtualbox.
Depois de clicar na opção “Download VirtualBox” selecione o seu Sistema
Operacional atual e o download será iniciado automaticamente, depois execute e
siga os passos de instalação, não tem segredo.
INSTALAÇÃO E INICIALIZAÇÃO DO CEUB-OS NO VIRTUALBOX.
Após a instalação do VirtualBox na sua máquina siga os passos a seguir para a
instalação e inicialização do CEUB-OS na sua máquina virtual.

PASSO 01: Neste site é onde está disponível as versões mais recentes do
CEUB-OS: https://sourceforge.net/projects/ceubos/files/build/
 Imagem: Nesse site é onde está disponível as versões do CEUB-OS para download.

PASSO 02: Após abrir o site vá até a opção “Download last version”, clicando nessa
opção você estará baixando a versão mais recente do CEUB-OS, após o clique o
seu download será iniciado automaticamente.
.
Download sendo iniciado automaticamente:

PASSO 03: Depois do download ser concluído você irá entrar no seu VirtualBox e
clicar em novo.
Imagem: Interface do virtualbox

PASSO 04: Depois de clicar em novo irá abrir asconfigurações. Na lacuna “Nome”
pode inserir qualquer nome, na configuração “Pasta da máquina”’será onde a
máquina virtual será armazenada e com isso você pode escolher o melhor local, na
configuração“Tipo”selecione a opção Linux, e na configuração “Versão” selecione
Debian 64 ou Debian 32 dependendo da quantidade de bits do seu computador,
após isso clique em “Próximo”.

PASSO 05: Nessa etapa você irá definir a quantidade de Memória RAM que terá
disponível na sua Máquina Virtual. Cuidado, não coloque muita Memória RAM pois
a sua máquina principal precisará também, então saiba balancear bem. Após isso
clique em próximo.

PASSO 06: Nessa etapa ele irá perguntar se você deseja criar um disco rígido
virtual, ou seja, ele vai criar um arquivo e o seu sistema irá interpretar como um HD.
Após isso clique em próximo.

PASSO 07: Nessa etapa não precisa fazer nada, apenas clicar em próximo.

PASSO 08: Agora deixe a opção “Dinamicamente Alocado” marcado, deixando
essa opção marcada o HD não ocupa espaço desnecessário. Logo após clique em
próximo.

PASSO 09: Essa etapa irá definir a quantidade de GB do seu HD na máquina
virtual. Escolha a quantidade de memória que irá atender às suas necessidades.
Após definir a quantidade de memória clique em “criar”.

PASSO 10: Sua máquina virtual está toda configurada, agora clique em “Iniciar”,
isso dará o boot na sua máquina.
Imagem: Dando boot na máquina virtual.

PASSO 11: Agora precisamos selecionar a ISO do CEUB-OS, essa ISO foi a que
baixamos no SourceForge. Para selecionar a ISO clique na pasta da direita.

PASSO 12: Após clicar na pasta vá até onde sua ISO está baixada, selecione e
clique em abrir.

PASSO 13: Após abrir a ISO clique em “escolher”.

PASSO 14: Nessa etapa clique somente em “iniciar”.

PASSO 15: Logo após só apertar a tecla “ENTER” do seu teclado, e começará a
dar o boot na sua máquina virtual.
Imagem: Dando boot na máquina virtual

PASSO 16: Depois de todas as etapas o CEUB-OS está pronto para ser utilizado na
máquina virtual.
imagem: inicialização do CEUB-OS na máquina virtual

CONCLUSÃO
Com base nas informações passadas podemos notar que baixar e instalar
uma distribuição Linux em um máquina virtual não é complicado. Ao longo do
processo usamos poucos softwares e fizemos configurações simples antes de dar o
boot na máquina.
Pode notar que mesmo o CEUB-OS sendo utilizado em uma máquina virtual
ele não perde a sua velocidade, pois é uma distribuição compacta e completa.

REFERÊNCIAS BIBLIOGRÁFICAS
https://azure.microsoft.com/pt-br/overview/what-is-a-virtual-machin
e/
https://e-tinet.com/linux/virtualbox-porque-utilizar/
