
### To do
- Corrigir >t com } único -> \pos(x,x) etc;
- Corrigir >te;
- Implementar >ocr OCR (Reconhecimento ótico de caracteres) <- Não é possível sem GPU ou CPU dedicado;
- Esperando a biblioteca googletrans se resolver; 
- Como usar; e
- NMT melhorado;

### Recursos

- Automação de tradução;
- Automção de revisão;
- Legendas de entradas .ASS e .SRT;
- Legenda de saída .ASS;
- Padrão Português Brasileiro;

### Algumas Bibliotecas Usadas
- [srt2ass](https://github.com/ewwink/python-srt2ass)
- [Discord.py](https://github.com/Rapptz/discord.py)
- [GoogleTrans](https://github.com/ssut/py-googletrans) OBSOLETO
- GoogleDocsAPI
- GoogleTranslateAPI


### Comandos Públicos
                    
Comando  |  O que faz | Entrada | Saída | Outro 
------------- | ------------- |--- |---| ----
`>t` | Traduz a legenda a partir do inglês | Hello World! | Olá mundo! | tradução de types entre {}
`>ta` | `>t` + matém a legenda em inglês na coluna "efeito" do aegisub | Hello World!  | Hello World! # Olá mundo! | 
`>te` | `>t` + Permite escolher os idiomas de entrada e saída |||
`>r` | Corrige vários erros como ôo, êe, éia, óia, etc. | Vôo, Cara ?!, Dêem, Idéia, Oi ...? | Voo, Deem, Ideia. Cara? Oi? |
`>txt` | converte a legenda para .txt |.ass ou .srt |.txt|
`>rsf` | remove sufixos '-chan', '-kun' | Inex-kun, inex-senpai | Inex, inex |
`>tt` | Traduz texto ou tabelas | >2000 caracteres |.txt |WIP |

### Como usar

### Convite Discord

[Convidar Kuon p/ Discord](https://discord.com/api/oauth2/authorize?client_id=745801652103020544&permissions=0&scope=bot "Kuon")

### Onde reportar erros, dar ideias?
Este bot ainda está em fase alfa, então não fique chateado se nada funcionar.
[Neste discord](https://discord.gg/QepxK7D) ou direto com o abençoado: inex#9779

