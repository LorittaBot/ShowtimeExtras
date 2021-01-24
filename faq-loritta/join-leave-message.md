title: "Como habilitar e configurar a mensagem de entrada e saída."
---
<img src="https://cdn.discordapp.com/attachments/397295975175028736/799989411063398400/loritta_welcomer.png" style="text-align: center;" height="300" />
Anuncie quem está entrando e saindo do seu servidor da maneira que você queria! Envie mensagens para novatos via mensagem direta com informações sobre o seu servidor para 
não encher o chat com informações repetidas e muito mais!

#### Comece escolhendo o servidor! Acesse o Painel de controle do servidor [clicando aqui](/dashboard) e escolha o servidor que deseja configurar!
![Passo](https://cdn.discordapp.com/attachments/397295975175028736/800008433692180520/Sem_Titulo-3.png)

#### Vamos habilitar o módulo! Ao ativar é essencial que escolha as opções abaixo que quer ativar, assim ela enviará a mensagem configurada!
![Passo2](https://cdn.discordapp.com/attachments/397295975175028736/800004766813257758/Sem_Titulo-3.png)


## Como configurar a entrada/saída de membros em um chat?
**1.** Marque as opções que deseja que a Loritta envie mensagem sobre a função! Lembre-se: Tem que configurar a mensagem.
![Passo3](https://cdn.discordapp.com/attachments/397295975175028736/800009208711086100/Sem_Titulo-3.png)

**2.** **IMPORTANTE!** Escolha os canais que vão enviar mensagem de saída e entrada de membros.
![Passo4](https://cdn.discordapp.com/attachments/397295975175028736/800004115555155988/Sem_Titulo-3.png)


## Como personalizar as mensagens?
**1.** Para personalizar as mensagens você tem que escolher entre usar ou não os Embeds.
* Se você for utilizar Embed [CLIQUE AQUI](/extras/faq-loritta/embeds) para ver todos os templates em detalhes.
* Se você não for utilizar Embed, basta ir ao tutorial mais abaixo para ver a explicação em detalhe de como usar.

**2.** Informe-se sobre as variáveis [clicando aqui](/extras/faq-loritta/placeholders), é importante por com ou sem embed.

## Configurando com Embed:
**1.** Você pode utilizar o template base para começar a linda edição do seu embed, com o código:
```json
{
   "content":"{@user}",
   "embed":{
      "color":-9270822,
      "title":"👋 Bem-vindo(a)!",
      "description":"Olá {@user}, espero que você se divirta no meu servidor! <:loritta:331179879582269451>",
      "author":{
         "name":"{user.tag}",
         "icon_url":"{user.avatar}"
      },
      "thumbnail":{
         "url":"{user.url}"
      },
    "footer": {
      "text": "ID do usuário: {user.id}"
    }
   }
}
```
**2.** Clique acima no botão **"EDITOR AVANÇADO"** e será levado a página para editar o embed, é bem simples!
![Passo6](https://cdn.discordapp.com/attachments/397295975175028736/799997345911537686/Sem_Titulo-3.png)

**3.** Agora é só clicar nas sessões e ir personalizado ao seu gosto! Lembrando de sempre por as variáveis [clicando aqui](/extras/faq-loritta/placeholders).
![Passo7](https://cdn.discordapp.com/attachments/397295975175028736/800021170673942578/Sem_Titulo-3.png)

**4.** Pronto! Agora é só ir na aba do Painel de Controle que a edição está lá, depois só ir ao fim da página e **"SALVAR"**.
![Passo8](https://cdn.discordapp.com/attachments/397295975175028736/800000482114011186/Sem_Titulo-3.png)

*P.S. Qualquer edição que você faça na página "EDITOR AVANÇADO" é colocado automaticamente no código, não FECHE o Painel de Controle.*

## Dicas
* Esse embed é apenas um exemplo, você tem infinitas personalizações! Veja sobre os Embeds [clicando aqui](/extras/faq-loritta/embeds).
* Coloque as variáveis necessárias [clicando aqui](/extras/faq-loritta/placeholders), para que exibir as informações básicas na mensagem.
* Se você quer personalizar o embed [clique aqui](https://embeds.loritta.website), basta copiar o código gerado após edição e pronto.

#### Se você seguiu todos os passos acima, o tutorial com embed acaba por aqui, espero que tenha ajudado! :)

## Configurando sem Embed:
**1.** Coloque a mensagem que deseja na caixa de diálogo, lembrando de colocar as [variáveis](/extras/faq-loritta/placeholders) junto.
![Passo9](https://cdn.discordapp.com/attachments/397295975175028736/800012222793252874/Sem_Titulo-3.png)

**2.** Pronto! É só salvar como preferir, essa configuração também vale para as outras funções como "Saída de membro".

#### Se você seguiu todos os passos acima, o tutorial sem embed acaba por aqui, espero que tenha ajudado! :)

## Como apago a mensagem da Loritta após a entrada/saída?
Para você que configurou a entrada de membros no `#bate-papo` do seu servidor e quer evitar a poluição ou só quer que depois de um tempo seja apagado, tem a opção que a Loritta
apaga a mensagem depois de uns tempo, basta ir abaixo da **"Mensagem de personalização"** de entrada e saída de membro e configurar o delay em segundos.
![Passo11](https://cdn.discordapp.com/attachments/397295975175028736/800016967783153684/Sem_Titulo-3.png)

## Como configuro pra Loritta enviar na DM após entrar?
**1.** Habilite nas configurações iniciais  *"Ativar as mensagens enviadas nas mensagens diretas do usuário quando alguém entrar"*.
![Passo12](https://cdn.discordapp.com/attachments/397295975175028736/800018245083332648/Sem_Titulo-3.png)

**2.** Na caixa de diálogo digite a mensagem ou cole o código embed [clicando aqui para ver os templates](/extras/faq-loritta/embeds).
![Passo13](https://cdn.discordapp.com/attachments/397295975175028736/800019347552337961/Sem_Titulo-3.png)

**3.** Pronto! Toda vez que algum membro entrar no seu servidor (que tiver o privado aberto), receberá a mensagem dando boas vindas!
![Passo14](https://cdn.discordapp.com/attachments/397295975175028736/800020159996887100/Sem_Titulo-3.png)

## Como vejo outros templates de embeds?
Para ver outros templates você pode [clicar aqui](/extras/faq-loritta/embeds) e ver quais outras formas de personalizar o seu lindo servidor tem disponível, como também
template para quando um membro é banido ou saí do servidor, também é necessário entender sobre as variáveis [clicando aqui](/extras/faq-loritta/placeholders).


