# Roteiro - Domínio e hospedagem de sites!

Nesse vídeo falarei sobre o os principais conceitos relacionados a domínio e hospedagem de sites e tudo o que você deve saber antes de comprar algum plano de hospedagem.

## Abertura do vídeo

Oie gente! Sejam bem vindos a mais um vídeo aqui do canal, eu sou a Rafaella Ballerini e hoje vou explicar pra vocês tudo sobre hospedagem de sites e domínios!

## O que seria hospedar um site?

Pegando um exemplo prático, lembram daquele [formulário](https://youtu.be/wwqOJ2o84S4) que ensinei vocês a desenvolverem aqui no canal? Então, a única forma que podemos acessá-lo no navegador sem ser abrindo o arquivo local ou com localhost, é hospedando essa nossa página com um serviço de hospedagem de site.

Vou então explicar pra vocês alguns termos relacionados a isso que eu conheço (deixando claro também que eu não sou expert em redes, então se você for e quiser agregar com mais informação o conteúdo que eu passar aqui, sinta-se a vontade para comentar aqui no vídeo!)

## O que é local host?

**É quando utilizamos o nosso computador para hospedar localmente o site, ou seja, apenas quem está conectado na nossa rede de internet poderá ter acesso.**
Um exemplo disso é quando usamos a extensão do VSCode "Live Server" ou o "Wamp Server" (tenho certeza que se você já mexeu com PHP na vida, você conhece essa ferramenta). Para utilizá-los normalmente colocamos na URL `localhost:porta` ou o `ipinterno:porta`- IPV4. Essa porta é um número que será gerado automaticamente por essas ferramentas que comentei.
Por sinal, pra você descobrir qual seria esse IPV4, você pode abrir o terminal e digitar `ipconfig` (Windows) ou `ifconfig` (outros sistemas), e ele irá listar para você.

<img src="https://media.discordapp.net/attachments/831974152667398214/850258701293322280/unknown.png">

E como falei, se você quiser abrir esse site com outro dispositivo que esteja conectado à sua internet, basta você colocar no navegador `ipinterno:porta`.

Eu vou mostrar isso pra vocês daqui a pouco!

## O que é domínio?

**É uma máscara do seu IP.** Como assim? Você **não** vai ter que digitar `ip:porta`, apenas o domínio do site.

Podemos pegar como exemplo o próprio Google. A gente não chega e digita o IPV4 deles com a porta (`142.250.218.46:80`) pra poder entrar no site, basta escrevermos `google.com` que conseguimos buscar o que quisermos na plataforma.

Então o domínio seria exatamente esse: `google.com`, sendo `.com` a sua extensão, que também pode variar dependendo de qual você escolher.

## Quais as vantagens de ter um domínio próprio e personalizado?

**1. Profissionalismo:** ter um domínio com o seu nome ou nome da sua plataforma dá um sensação de quem entra no site que seu serviço ou produto é mais confiável, não tem jeito. 

**2. Marca:** isso torna muito mais fácil para as pessoas gravarem a sua URL para caso queiram entrar lá novamente. 

**3. Indexação:** caso você não tenha um domínio próprio, você não vai aparecer nas páginas principais dos buscadores da internet (como Google e DuckDuckGo). Então é ótimo para quando as pessoas buscarem por algo relacionado ao seu serviço ou produto, seu site já aparecer lá na frente.
 
## O que é então um serviço de hospedagem?

**É um serviço online que permite que você "publique" seu site ou aplicação na internet**, deixando assim aberta para qualquer pessoa que digitar o seu domínio no navegador.

Além disso, ele deixa sua aplicação rodando 24h por dia, então seu site sempre ficará no ar!

# Como hospedar - Passo a passo com a Hostinger

Para mostrar agora pra vocês como funciona, vou utilizar o serviço da [Hostinger](https://www.hostinger.com.br/), que **é uma plataforma de hospedagem pensada justamente para quem está iniciando nessa área por ser muito rápida, prática e o suporte deles também estar disponível 24h por dia caso aconteça alguma coisa!**

Que inclusive está patrocinando esse vídeo! Então se vocês quiserem agradecer a alguém pelo conteúdo, pode ir lá no instagram da Hostinger e deixar um "Obrigada pelo patricínio no vídeo da Rafa!" no último post deles 😊

Eu desenvolvi um site estático essa semana pra poder usar de exemplo e vocês verem. Por sinal, ele foi feito para dispositivos móveis, então se você abrir aqui no desktop, não julgue o design, ainda quero melhorar a responsividade!

### Compra do serviço

* Primeira coisa que fazemos então é abrir o [site deles](https://www.hostinger.com.br/) e escolher um plano. Por sinal eles tem um ótimo custo-benefício!
No caso eu estou usando o plano Business, mas vocês escolhem o que melhor se adequa às suas necessidades!
* Selecione o período que você quer utilizar e caso você ainda não tenha um domínio, você poderá colocar um no carrinho também
* Vocês podem utilizar o meu cupom de desconto **RAFA** (que estará disponível no comentário fixado do vídeo) e finalizar a compra

### Configurando

Agora iremos configurar a nossa hospedagem e para isso basta clicar na página inicial em `configurar`.

Abrirá um passo a passo em que você adicionará suas informações de contato, domínio escolhido e o seu site estará pronto!

Ao abrir, a plataforma pediu para que eu apagasse o arquivo `default.php` por FPS ou pelo gerenciador de arquivos.

Então, no gerenciador de arquivos, apaguei o arquivo que deveria e quando recarreguei meu site, percebi que ele estava direcionando para a minha pasta, e não os arquivos dentro dela.

Assim, fui novamente no gerenciador de arquivos da plataforma e movi todos os arquivos dentro da pasta `Rafaella Ballerini` para fora dela.

**E PRONTO! Meu [site](https://rafaballerini.tech) funcionando perfeitamente!**

Para finalizar, apaguei a pasta `Rafaella Ballerini` no gerenciador de arquivos, que já não tinha mais nada e também fiz a instalação do certificado SSL, presente no painel de controle.

**Não esqueçam de deixar o like e se inscrever no [canal do Youtube ❤](https://youtube.com/RafaellaBallerini)**

Até semana que vem, um beijo!
