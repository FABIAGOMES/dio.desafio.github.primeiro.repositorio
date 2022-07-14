# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto

## Links úteis
[Sintaxe Básica Markdown] (https://www.markdownguide.org/basic-syntax/)

Porque aprender Git e GitHub?
Grande parte das empresas que tem um ramo de TI, seja esta uma startup ou multinacional, versionam o código usando essas ferramentas. Imagine o cenário com 100 programadores fazendo mudança em um mesmo código. Sem um versionamento, viraria uma bagunça! O versionamento com Git veio para sanar esse tipo de situação. Além disso, o GitHub virou uma "vitrine" de códigos para o programador. Enquanto recrutadores de designers olham o portfolio de quem quer ser contratado, recrutadores de programadores das empresas olham - além do seu currículo - seu código. É através dessa vitrine que a empresa identifica como é seu estilo de programação, quais as linguagens que têm mais interesse, quais projetos open source você contribui no momento.

Git é uma ferramenta de controle de versão e serve para:
- Gerenciamento de versões de um documento de texto qualquer, alterações e guarda o histórico delas.
 O versionamento de código funciona como uma espécie de backup:
- Melhora o trabalho em equipe pois permite que várias pessoas trabalhem no mesmo conjunto de arquivos (repositórios) e evita conflitos entre as alterações 
- Resgate de versões estáveis, permite que você retorne para uma versão antiga, no caso de algum bug no software.
-Segurança, somente pessoas autorizadas pela empresa podem mexer no código.

Importante, o git não precisa do GitHub para existir, porém o GitHub é altamente dependente do git para existir.

Resumo dos comandos de fluco de trabalho do git e o que fazem:
•	git init: inicializa um repositório local git
•	git status: verifica o estado dos seus arquivos
•	git add <nomeDoArquivo>: envia seu arquivo especificado para o Stage
•	git add - -all: envia todos os arquivos para o Stage
•	git commit -m “tituloDoCommit: envia o que está no Stage para o HEAD
•	git remote add origin urlDoRepositorio: adiciona e indica a URL do repositório remoto em que os arquivos serão mantidos
•	git push origin master: envia os arquivos para o repositório remoto que você especificou através da URL do comando acima
•	git checkout -b <nomeDaBranch>: cria uma nova branch
•	git checkout <nomeDaBranch>: alterna para a branch especificada

Git Bash :
Todo esse fluxo descrito acima é manipulado através do Git Bash (caso você utilize Windows). Contextualizando, o Git foi feito inicialmente para rodar em sistemas Unix, que não é o caso do Windows. Assim, foi criado o Git Bash, uma aplicação que emula um terminal Unix e permite que você desfrute dos comandos Git. O Git Bash já vem no pacote de instalação do Git para Windows.

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. É como uma plataforma social colaborativa, onde programadores e empresas colocam seus projetos para o desenvolvimento do código.

Link de Instalação do git no Windows : https://git-scm.com/download/win, 
Como verificar se o git foi instalado corretamente:
Na barra de busca do Windows, clique CMD, para a abrir seu prompt de comando, ao abrir, digite: “git –version”, se aparecer a versão do git, é porque ele foi instalado corretamente 

Link de Instalação do git no Linux https://git-scm.com/download/linux

Link de Instalação do Git no mac https://git-scm.com/download/mac

Para configurar nome de usuário no git:
Digite :git config --global user.name “Usuario 123” 
para conferir se deu certo, digite :git config --global user.name 

Como usar o GitHub
Vamos ao nosso GitHub tutorial sobre como utilizar o GitHub com os principais passos na ferramenta.

Antes, você precisa criar sua conta pessoal ou uma conta de equipe na página oficial do GitHub. 
É totalmente gratuito para repositórios pessoais e para times, como alguns planos pagos mais avançados para times e empresas.
Depois de criar sua conta, utilize o Hello World Guide da plataforma para saber como criar o seu primeiro repositório, fazer um branch ou abrir um pull request.

Um repositório é um espaço em que todos os arquivos de um projeto específico são armazenados. 
Cada projeto tem seu próprio repositório e você pode acessá-lo com um URL exclusivo.

O que é um fork?
“Forking” é quando você cria um novo projeto baseado em outro projeto que já existe, como a bifurcação de um caminho. 
Esse é um recurso que incentiva amplamente o desenvolvimento de programas e projetos entre a comunidade ou entre equipes, de forma geral. 
Digamos que, ao você encontrar um projeto no GitHub com o qual gostaria de contribuir, poderá dividir o repositório, fazer as alterações desejadas e liberar o projeto revisado como um novo repositório. 
Se o repositório original que você criou para criar seu novo projeto for atualizado, você poderá facilmente adicionar essas atualizações ao seu fork atual.

GitHub Pages: montando seu portfólio de códigos
Além de ser um repositório de códigos e rede social, o GitHub ainda oferece a possibilidade de hospedagem de mini-sites estáticos, quantos você quiser! 
Isso é uma ótima maneira para os desenvolvedores criarem e divulgarem seus códigos diretamente.

Há duas maneiras de construir suas páginas no GitHub: com o GitHub Theme Chooser, ou escrevendo o código do zero.

Antes de começar, é preciso preparar seu GitHub para hospedar seu site. Aqui vai um passo a passo resumido para isso:
1.	Crie um novo repositório chamado username.github.io, trocando o username pelo seu nome de usuário no GitHub. Este será o repositório do seu site e o GitHub automaticamente o reconhecerá como a sua home page
2.	Crie o arquivo index.html com o que você quiser que apareça na sua página. Um “Hello world” para teste é suficiente
3.	Faça um add, commit e um push para visualizar as mudanças

Você também pode baixar templates para seu portfólio. 

Há também a opção do GitHub Résumé, que gera um currículo a partir das informações do seu GitHub. 
Um resumo com as linguagens que utiliza, projetos que participa e seus repositórios mais populares são organizados automaticamente.

O que colocar no GitHub?
Depois da sua página pronta, chega a hora de colocar seus projetos para o acesso de quem estiver interessado. E aí vem a dúvida: o que colocar no portfólio?
Resumindo em uma palavra: TUDO!

Aquele seu projeto pessoal ou da faculdade que você acha que não serve para nada, pode conter algum conceito ou técnica de programação que alguma empresa procura.
Fez um curso complementar de programação onde teve que desenvolver algum projeto? Coloque-o no GitHub. Tem um projeto pessoal sendo desenvolvido, coloque-o também. 
Além do seu código ficar visível para o mundo, pessoas ainda podem ajudá-lo a desenvolvê-lo.
Se você já é programador e desenvolve para uma empresa, muito provavelmente não poderá divulgar seu código. Neste caso crie projetos simples com a tecnologia e metodologia que está usando e coloque no GitHub, descrevendo tudo o que fez

O README do GitHub
Um elemento importante para os seus projetos mas que nem sempre recebe a devida atenção é o arquivo README.
O README é a primeira impressão do seu trabalho. Sempre tenha um na raiz do projeto. 
Um bom README é aquele que contém uma boa descrição do objetivo, onde e como usar, lista de funcionalidades, dependências para funcionar. Exemplos de uso será um plus.

Lembre-se que o README é para ser um resumo, não uma documentação do projeto. Para a documentação, você pode utilizar a Wiki do próprio GitHub.

Adicionar um repositório do computador local ao GitHub Desktop
É possível adicionar qualquer repositório Git ao GitHub Desktop, mesmo que não seja um repositório do GitHub
Dica: é possível adicionar um repositório Git do computador local ao GitHub Desktop arrastando a pasta para a janela do GitHub Desktop. Ao arrastar várias pastas do Git para o GitHub Desktop simultaneamente, cada pasta será acessada como um repositório Git individual.
1- No menu File (Arquivo), clique em Add Local Repository (Adicionar repositório local).
2- Clique em Choose... (Escolher...). Em seguida, navegue pela janela Windows Explorer (Explorador do Windows) até o local do repositório que você pretende adicionar.
3- Clique em Add Repository (Adicionar repositório).


Como incluir, atualizar e baixar um projeto do GitHub usando os comandos git. O tutorial a seguir considera que o git já está instalado, configurado em sua máquina e que você sabe usar os comandos básicos do git no Git Bash.

Como incluir um projeto no GitHub
Para incluir um projeto de sua máquina local no GitHub siga os passos abaixo:

1. Crie o repositório no GitHub sem o arquivo readme.md, sem licenças e sem o arquivo .gitignore, esse arquivo pode ser incluído depois no primeiro commit.

Após incluído o projeto guarde a url do repositório. Você pode obter a url no site do GitHub selecionando o botão Code na tela principal do repositório.
Para fazer o controle de versão do projeto localmente e seguir os próximos passos o git deve estar instalado e configurado em sua máquina. Se quiser obter mais informações de como instalar, configurar e usar o git você pode acessar o livro Pro Git on line gratuitamente. 

2. No diretório do projeto local inicie o controle de versão do git:
git init

3. Insira todos os arquivos do projeto no controle de versão do git:
git add .

4. Faça o commit do projeto:
git commit -m "descrição breve do commit"

5. Configure no projeto local o endereço do servidor do repositório no GitHub:
git remote add origin [endereço do repositório GitHub obtido no item 1]

6. Confira se o endereço do repositório do GitHub está correto no projeto local:
git remote -v

7. Envie o projeto de seu computador para o GitHub:
git push -u origin master

Como atualizar um projeto no GitHub
Para atualizar um projeto de sua máquina local no GitHub e fazer o controle de versão siga os passos abaixo:

1. Insira todos os arquivos alterados do projeto no repositório local do Git:
git add .

2. Faça o commit do projeto. O flag -m permite colocar uma frase curta descrevendo a alteração executada no projeto:
git commit -m "descrição breve do commit"


3. Envie o projeto local para o branch master no GitHub. Caso esteja trabalhando em outro branch, substitua o nome master pelo nome do branch:
git push -u origin master

Como baixar um projeto do GitHub
Para começar a trabalhar em um projeto hospedado no GitHub é necessário baixar o projeto para a máquina local. O recomendado é trabalhar em um branch ao invés de trabalhar no projeto masterenquanto está em fase de desenvolvimento.

Para baixar um projeto do GitHub para sua máquina local siga os passos abaixo:

1. Faça o clone do projeto do GitHub em sua máquina:
git clone [url do repositório no GitHub]

Se você for trabalhar no branch master já pode iniciar suas alterações e atualizar o GitHub quando finalizar. Caso queira trabalhar em um branch diferente do master continue os próximos passos.

2. Altere o projeto local para trabalhar com o branch desejado:
git checkout [nome do branch]

3. Se quiser verificar os branches que estão no repositório local:
git branch

4. Se quiser visualizar os branches que estão no projeto local e no GitHub:
git branch -a

Agora que você viu como é fácil usar o Git para incluir, atualizar e baixar o seu projeto no GitHub aproveite para usar esse excelente recurso que é gratuito, para organizar e armazenar todos os seus códigos. 







