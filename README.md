# MM2 Trade Hub 🔫🔪

> Real-time MM2 Values and Trade Calculator. (WIP)

🌎 **Choose your language / Escolha seu idioma:**
* [🇺🇸 English](#-english-version) *(Coming soon)*
* [🇧🇷 Português (Brasil)](#-versão-em-português)

---

## 🇧🇷 Versão em Português

Bem-vindo ao **MM2 Trade Hub**! Esta é uma ferramenta (atualmente em desenvolvimento) criada para ajudar os jogadores de Murder Mystery 2 a calcular trocas de forma rápida e visual. 

O objetivo final é criar um "overlay" inteligente que leia os valores reais da economia do jogo direto da sua tela, facilitando na hora de saber se uma troca vai te gerar Ganho, Perda ou se não vai mudar nada (Justa).

### 📖 A História, a Refatoração e Quem Sou Eu
Quem joga MM2 sabe a tensão que é ter que calcular valores correndo rápido para o outro jogador não cancelar a troca, ou pior, tomar *scam* porque não deu tempo de somar tudo. 

A primeira versão desse projeto nasceu não para mim, mas para ajudar a minha namorada, que jogava muito MM2 e fazia dezenas de trocas por dia. Para facilitar a vida dela, criei um script em Python que reconhecia a tela e fazia o cálculo matemático. Até funcionava, mas era uma ferramenta muito limitada, pesada e lenta.

Vendo o quanto isso podia ajudar na prática, decidi **refatorar tudo do zero**, mas dessa vez para a comunidade inteira. O projeto atual está sendo construído com uma base robusta e moderna usando **React e Rust**, e fazendo a substituição daquele script antigo por um modelo real de Inteligência Artificial, trazendo uma interface limpa, rápida e 100% automatizada.

**Um aviso rápido sobre mim:** Sou apenas um adolescente de 17 anos no 3º ano do Instituto Federal. Estou desenvolvendo o MM2 Trade Hub como um "hobby" e com muita paixão, mas como estou no meu último ano, tenho meu TCC e outros compromissos pesados para conciliar. Prometo manter o máximo de compromisso possível para fazer esse projeto dar certo e chegar até a linha de chegada!

---

### 📸 O que já está pronto

O projeto está ganhando vida na interface gráfica! Aqui estão algumas prévias da interface atual rodando lado a lado com o jogo:

![Troca em Tempo Real](trade-pt.jpg)
![Tela de Simulação](sml-pt.jpg)
![Tela de Configuração](config-pt.jpg)

---

### 🤖 Inteligência Artificial (Preciso de Você!)

As telas acima mostram o visual do projeto pronto, **mas no momento o cálculo em tempo real é estático**. 

Para que o aplicativo seja 100% automático, estou treinando um modelo de Visão Computacional (IA) para ler a janela de trade do Roblox. E é exatamente aqui que eu **preciso da ajuda da comunidade!**

**📊 Progresso atual do treinamento da IA:**
O modelo já está com **87.0% de precisão geral**, mas temos um grande obstáculo visual:

* ✅ `gui_inventory`: 100%
* ✅ `gui_trade`: 100%
* ✅ `offer_label`: 100%
* ✅ `trade_progress`: 100%
* ✅ `trader_nickname`: 100%
* ✅ `weapon_icon`: 100%
* ✅ `weapon_name`: 100%
* ❌ **`quantity` (Quantidade ex: x2, x3, x4): 0.0%**

A IA está perfeita para ler nomes e ícones de armas, mas **ela está completamente cega para os multiplicadores de quantidade**. 

**🤝 Como você pode ajudar a treinar o modelo?**
Neste primeiro momento, o nosso foco é **100% na interface de Computador (Desktop)!** Eu preciso de um volume gigante de imagens para a IA aprender. Se você joga MM2 no PC, **tire prints em tela cheia** das suas janelas de troca, especialmente daquelas que tenham itens repetidos (x2, x3, x4)! (Não são necessárias negociações reais, apenas o visual).

*(Nota: Telas onde a janela do Roblox fique visualmente idêntica à do PC também são bem-vindas. Futuramente, se tudo der certo, vou tentar lançar uma versão Mobile do app, e aí pedirei novamente a ajuda de vocês com prints de celular!)*

*Exemplos de prints perfeitas para me enviar:*
![Exemplo de Dados de Treino 1](print1.jpg)
![Exemplo de Dados de Treino 2](print3.jpg)

**📥 Onde enviar as prints?**
Para facilitar, criei um Google Forms rápido para receber os uploads. 

🔗 **[Clique aqui para acessar o formulário e enviar suas prints!](https://forms.gle/JYyAPSXY3MkQj6rx6)**

![Formulário de Upload](img/forms.png)

⚠️ **Aviso legal:** Se você deixar seu nick do Discord ou Roblox lá no forms, seu nome vai aparecer no futuro **'Mural de Apoiadores'** do aplicativo como forma de agradecimento!🏆

---

### 🛠️ Status do Projeto
- [x] Interface Visual (UI/UX) inicial
- [x] Sistema de Simulação de Trocas
- [x] Tela de Trocas ao Vivo
- [x] Internacionalização (PT-BR implementado)
- [ ] Integração com os Valores em Tempo Real da Economia
- [ ] Conclusão do Modelo de IA de Leitura de Tela (Treinamento em andamento 🚀)

---

### ☕ Apoie o Projeto (Em Breve)
Todo esse ecossistema leva tempo, dedicação e muita energia para ser construído! Futuramente, vou criar plataformas de apoio (como Apoia.se, Buy Me a Coffee, etc.) onde vocês poderão apoiar o desenvolvimento do projeto. 

**Por que "Em Breve"?** Eu só vou liberar as plataformas de apoio financeiro quando o aplicativo estiver na reta final e eu tiver certeza de que não terei imprevistos com o meu TCC ou com a escola. Eu acho muito "paia" receber o apoio de vocês e não conseguir entregar a ferramenta prometida.

Quando chegar a hora, os fundos serão totalmente separados por transparência:
* 🚀 **Apoie o App (Infraestrutura):** Todo valor arrecadado aqui será destinado **100% ao projeto**. O objetivo é usar isso para coisas como: alugar servidores VIPs próprios para a comunidade do MM2 Trade Hub negociar.
* ☕ **Me pague um café (Desenvolvedor):** Um apoio direto e pessoal a mim, para ajudar a manter o foco nas madrugadas de código! 😁

---

### 🤝 Futuras Parcerias e Anúncios
Quando o projeto estiver bem próximo da reta final, abrirei espaço para parcerias oficiais! 

Sendo bem transparente sobre a questão de anúncios: eu odeio aqueles banners aleatórios do Google poluindo a tela. Portanto, **SE** eu chegar a colocar anúncios no aplicativo, prometo que não serão coisas chatas que vão atrapalhar a sua experiência ou a sua tela. A ideia é trazer apenas recomendações bem "based" e úteis para quem joga, como lojas confiáveis para comprar Robux ou para comprar armas do MM2. Tudo 100% focado no universo Roblox!

💖 **Muito obrigado por ler até aqui, e um agradecimento gigante a todos que estão enviando suas prints e ajudando a transformar esse projeto em realidade!**