
# Jekyll para todos

O Jekyll For Everyone é um pacote projetado para todos. O pacote contém três componentes principais: página inicial, CV e [Gitbook] (http://www.gitbook.com). A página de índice é uma versão simplificada do [Jekyll Uno] (https://github.com/joshgerdes/jekyll-uno) enquanto o CV é uma modificação do [Online CV] (https://github.com/sharu725/online -cv). No entanto, o [Legit Gitbook (v3.2.3)] (https://github.com/GitbookIO/gitbook) é usado em vez do Gitbook moderno (v4 +). A principal razão de usá-lo é devido ao fato de que os usuários podem possuir seu código-fonte e editá-lo localmente, em vez de fazê-lo na nuvem.

Este pacote é muito amigável para não programadores, pois reorganizei todos os arquivos e tenho todas as variáveis ​​escritas em vários arquivos de dados. Isso faz com que eles editem sem precisar entrar no código real.

Muito obrigado ao criador do tema, pois este projeto não seria possível sem o trabalho duro deles! Você é sempre bem-vindo a contribuir com este repositório para torná-lo melhor!

** História por trás do projeto **

O principal objetivo deste projeto é permitir que todos, especialmente os não programadores, possuam um site e uma plataforma para compartilhar seus conhecimentos sem precisar se preocupar com o custo de propriedade e manutenção do site. Eu ouvi muitos leitores mencionando que eles estão apaixonados pela simplicidade do meu site, especialmente e adorariam um. Eles só raciocinam que os impedem de fazê-lo é que eles não têm nenhuma experiência em programação e não são conhecedores de tecnologia. Com isso, isso me motiva a escrever um tutorial completo sobre como começar com [Jekyll] (http://melvinchng.github.io/jekyll).

Além disso, como recém-formado, vejo a importância de possuir um site pessoal quando se trata de procurar emprego. Se você ama este projeto e gostaria de apoiá-lo, espalhe a mensagem e mantenha o rodapé como está.

** Site de exemplo **
- Meu site pessoal
  - [Página de destino de Melvin] (https://melvinchng.github.io)
  - [CV de Melvin] (https://melvinchng.github.io/cv)
  - [Tutoria Ruby on Rails de Melvin] (https://melvinchng.github.io/rails)
- Site de exemplo de Jekyll para todos
  - [Página de destino] (https://jekyll-for-everyone.github.io)
  - [CV] (https://jekyll-for-everyone.github.io/cv)
  - [Gitbook] (https://melvinchng.github.io/gitbook)

_Nota: O conteúdo em `jekyll-for-everyone` é apenas para fins ilustrativos. Pode não conter informações precisas._

## Recursos
### Página de índice
- Nome
- Linha de título
- Linha de informação secundária
- Links para páginas sociais
- Links para outras páginas
### CV
- Resumo ou Histórico
- Educação
- Experiências
- Projetos Individuais
- Projetos em grupo
- Habilidade e Proficiência
- Cursos relacionados
- Honras e prêmios
- Línguas
- Link social
- Experiências Voluntárias
### Gitbook
- Exemplo de Gitbook

## Instalação
### Se você não sabe o que está fazendo
1. Consulte o meu [guia] (http://melvinchng.github.io/jekyll). Ele contém instruções únicas que você precisa seguir para começar.
### Se você sabe o que está fazendo ou sabe o que fazer
** Jekyll **
1. Para usuários iniciantes, você deve instalar o Ruby e o Rails. Se você não possui o Ruby instalado, siga este [tutorial] (http://melvinchng.github.io/rails/RubyOnRailsInstallation.html) que escrevi para Windows, Linux e MacOS (vídeos de instalação estão incluídos).
2. Instale o Jekyll usando o comando `gem install jekyll`.
3. Em seguida, instale o Jekyll Sitemap e o Jekyll SEO gems usando o comando `gem install jekyll-sitemap` e` gem install wdm`.
4. Inicie o servidor localhost usando o comando `jekyll serve`. Verifique se você está no diretório raiz da sua pasta antes de usar este comando.
5. Seu site deve estar acessível em `localhost: 4000`.
6. Para informações adicionais sobre o Jekyll, consulte o [site oficial] (http://jekyllrb.com/).

** Gitbook **
1. Para usuários iniciantes, você precisa dos módulos do Gitbook usando o comando `npm install gitbook-cli -g`.
2. Navegue até o diretório raiz do gitbook, `gitbook_source_code` e inicie o servidor gitbook usando o comando` gitbook serve`.
3. Se faltam alguns pacotes para o gitbook, use o comando `gitbook install`.
4. Seu site deve estar acessível em `localhost: 4000`.
5. Para obter informações adicionais sobre o Gitbook, consulte o [site oficial] (https://github.com/GitbookIO/gitbook).

## Como usar
### Página de índice
- A folha de estilo, scripts, javascript para as páginas de índice são armazenadas em `/ index_style /`.
- A imagem de fundo da página de índice, denominada `background-cover.jpg`, pode ser encontrada e substituída em` index_style / images`.
- A imagem do perfil da página de índice e da página cv, denominada `profile.png`, pode ser encontrada e substituída em` assets / images`.
- Todos os dados mostrados na página de índice são armazenados em `/ _data / index_page.yml`. Substitua todo o conteúdo dos arquivos.

### CV
- A folha de estilo, scripts, javascript para as páginas cv são armazenadas em `/ assets /`.
- Todos os dados mostrados no CV são armazenados em `/ _data / cv_NAME.yml`. Substitua todo o conteúdo dos arquivos.
- Se você gostaria de voltar
Enviar feedback
Histórico
Salvas
Comunidade

### Gitbook

     Se você não usar o recurso Gitbook, remova a pasta gitbook.
     O código fonte é armazenado em / gitbook_source_code
     O conteúdo do livro gerado é copiado de / gitbook_source_code / _book para / gitbook.

### De outros

     Se você deseja substituir o ícone do site, pode usá-lo para criar um e substituir o ícone baixado em favicon.io.
     Atualize a variável em /_config.yml. Lembre-se de substituir a variável url pelo seu URL real.
     Se você deseja usar o Google Analytics, adicione seu número de rastreamento a /_config.yml.

### Aproveite!

Como lembrete, se você ama este projeto e gostaria de apoiá-lo, espalhe a mensagem e faça um fork.
