# Atividade Ponderada SI10 semanas 2 a 8


## Parte 1: Análise HEART e GSM + proposta de coleta de dados

### Introdução

O YouTube é uma plataforma de compartilhamento de vídeos que se estabeleceu como um gigante no cenário digital, podendo ser adotado no papel que a televisão desempenha para seus usuários. Com sua variedade de conteúdo, produzido diretamente por criadores de conteúdo, que vai desde tutoriais e vlogs até entretenimento e notícias, o YouTube tornou-se uma fonte de informação e lazer. 

A escolha do YouTube para a análise de experiência do usuário (UX) se deve por sua posição de destaque no dia a dia dos usuários, e pela sua relevância ainda nos dias de hoje, oferecendo streaming de vídeos em larga escala. Desde o seu lançamento em 2005, o YouTube tem vem estabelecendo padrões e influenciando o desenvolvimento de outras plataformas de mídia. 

Contudo, apesar de seu sucesso e inovação, o YouTube enfrenta desafios contínuos em termos de experiência do usuário. Por exemplo, a navegação e a descoberta de conteúdo relevante são aspectos que frequentemente frustram os usuários, como pode ser verificado na figura 1, inundados por recomendações que nem sempre atendem aos seus interesses, em uma disposição que mistura conteúdos de temas diversos. 

Esses problemas apontam para a necessidade de uma avaliação aprofundada da interface e da arquitetura de informação do YouTube, com o intuito de identificar oportunidades de otimização. Com isso, serão utilizados o framework HEART e o modelo GSM para analisar sistematicamente a experiência do usuário, formular hipóteses baseadas no problema central onde os usuários não encontram vídeos relevantes para eles a partir da página inicial do YouTube, e também realizar observações a partir de testes de usabilidades e coletas de dados qualitativas e por fim testá-las por meio de uma proposta de coleta de dados. 

 <img width="1326" alt="image" src="https://github.com/Inteli-College/2024-1B-T04-SI10-G04/blob/main/imgs/youtube.png">
Figura 1. Página inicial do YouTube. (Diretamente extraído do meu YouTube pessoal).

_


É importante observar que o maior espaço disponível em sua interface é dedicado aos conteúdos em vídeo, destacado em um retângulo vermelho na figura 2, sendo que dois desses vídeos são anúncios, destacados em amarelo. No retângulo azul estão notícias publicadas na plataforma por agências de notícias e blogs, deixando disponível para vídeos de recomendação o restante da da área que foi marcada com o retângulo vermelho, sendo o conteúdo que será analisado neste trabalho.

 <img width="1326" alt="image" src="https://github.com/Inteli-College/2024-1B-T04-SI10-G04/blob/main/imgs/youtube1.png">
Figura 2. Página inicial do YouTube, com seus elementos destacados em grupos, relacionando suas features. (Diretamente extraído do meu YouTube pessoal).


### Framework HEART com o framework GSM 

| Framework HEART          | Objetivo (Goal)                                                                                                                                                   | Sinal (Signal)                                                                                                                      | Métrica (Metric)                                                                                                                                                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Felicidade (Happiness)**   | Que o usuário fique satisfeito com as recomendações de vídeos na página inicial.                                                                                | Nível elevado de engajamento e feedbacks positivos nos vídeos acessados a partir da tela inicial.                                   | <ul><li>Taxa de curtidas em vídeos acessados na página inicial. </li><li>Tempo assistido de vídeos acessados da página inicial.</li></ul>                                                                                                                       |
| **Engajamento (Engagement)** | Melhorar a interação dos usuários com a seção de recomendações, fazendo-os explorar mais vídeos de seus canais preferidos e descobrir novos conteúdos.            |<ul><li> Aumento de vídeos assistidos por sessão.</li><li>  Sessões mais longas por usuário. </li></ul>                                                          |  <ul><li> Quantidade de vídeos assistidos que são recomendações da página inicial, em relação a vídeos assistidos por buscas manuais.</li><li> Tempo médio por vídeo assistido a partir da página inicial, em relação a vídeos assistido por busca direta.</li></ul> |
| **Adoção (Adoption)**        | Que o usuário passe a utilizar mais frequentemente as recomendações personalizadas da página inicial para descobrir vídeos de interesse.                                                              | Aumentar o número de usuários que seguem as recomendações personalizadas ao invés de usar a busca direta.                           | Quantidade de cliques em vídeos de recomendação a partir da tela inicial, em relação a vídeos acessados via busca direta.                                                                                                           |
| **Retenção (Retention)**     | Manter os usuários voltando à página inicial do YouTube e utilizando recomendações de vídeos para encontrar conteúdo de seu interesse.                             | Maior retorno à tela inicial para acessar novas recomendações de vídeos.                                                            | <ul><li>Frequência de retorno dos usuários à página inicial. </li><li>Proporção de sessões que começam com a visualização de um vídeo recomendado. </li></ul>                                                                                                   |
| **Sucesso da Tarefa (Task Success)**  | Otimizar o sucesso dos usuários em encontrar rapidamente vídeos novos de canais específicos ou conteúdos interessantes de canais desconhecidos na página inicial. | Aumentar cliques em vídeos recomendados na página inicial.      | Quantidade de vezes em que a página inicial é atualizada até um vídeo ser clicado.                      |

### Hipóteses Levantadas

Problema: Os usuários não encontram vídeos relevantes para eles a partir da página inicial do YouTube.

**Hipótese 1:** As recomendações de vídeo não são relevantes para os interesses dos usuários.

- Justificativa da Coleta de Dados: Coletar dados sobre a taxa de cliques em vídeos de recomendação na página inicial e a taxa de curtidas nesses vídeos ajudará a avaliar a relevância das recomendações. Uma baixa taxa de cliques e curtidas pode indicar que as recomendações não estão alinhadas com os interesses dos usuários.

**Hipótese 2:** A interface da página inicial não é intuitiva, dificultando a navegação e descoberta de vídeos.

- Justificativa da Coleta de Dados: Analisar a frequência de retorno dos usuários à página inicial e a quantidade de vezes que a página inicial é atualizada até um vídeo ser clicado pode revelar se os usuários estão tendo dificuldade em encontrar vídeos. Se os usuários estão atualizando a página frequentemente sem clicar em vídeos, isso pode indicar problemas de usabilidade na interface.

**Hipótese 3:** Os usuários preferem buscar vídeos em vez de usar as recomendações da página inicial.

- Justificativa da Coleta de Dados: Coletar dados sobre a proporção de sessões que começam com a visualização de um vídeo recomendado versus aqueles que começam com uma pesquisa pode ajudar a entender se os usuários estão preferindo usar a barra de pesquisa. Uma baixa proporção de vídeos recomendados assistidos pode sugerir que os usuários preferem buscar vídeos manualmente.

**Hipótese 4:** A personalização das recomendações não está suficientemente adaptada ao comportamento passado do usuário.

- Justificativa da Coleta de Dados: Monitorar a quantidade de vídeos assistidos que são recomendações da página inicial e o tempo assistido de vídeos acessados da página inicial pode fornecer insights sobre a eficácia da personalização. Se os usuários estão assistindo poucos vídeos recomendados ou assistindo por pouco tempo, isso pode indicar que as recomendações personalizadas não são eficazes.


### Ferramentas e Coleta de Dados

**1. Google Tag Manager (GTM):** 

GTM pode ser usado para configurar e gerenciar tags de rastreamento de eventos JavaScript, para capturar eventos como cliques e interações com o vídeo.

**- Métricas:**
    
    - Taxa de curtidas em vídeos acessados na página inicial.
    
    - Tempo assistido de vídeos acessados da página inicial.
    
    - Quantidade de vídeos assistidos que são recomendações da página inicial.
   
    - Tempo médio por vídeo assistido a partir da página inicial.

**-  Configuração Necessária:** Para rastrear essas métricas específicas, é necessário configurar gatilhos e tags correspondentes dentro do GTM. Por exemplo, configurar gatilhos para detectar quando um usuário clica em um botão de "curtir" ou inicia a reprodução de um vídeo.

Necessário também configurar variáveis dentro do GTM para capturar informações adicionais, como a duração do tempo assistido ou se um vídeo foi assistido a partir de uma recomendação na página inicial.

A integração com o Google Analytics ou outras plataformas de análise pode ser necessária para enviar esses dados capturados para análise mais aprofundada.

**2. Google Analytics:**

Ferramenta de análise web que pode ser integrada com o YouTube para fornecer dados mais aprofundados sobre o comportamento dos usuários no site.

**- Métricas:**
   
     - Quantidade de cliques em vídeos de recomendação a partir da tela inicial.
     
     - Frequência de retorno dos usuários à página inicial.
     
     - Proporção de sessões que começam com a visualização de um vídeo recomendado.

**- Configuração Necessária:** Pode exigir a configuração de eventos personalizados para rastrear cliques em recomendações específicas e a interação com a página inicial.

**3. Desenvolvimento de Software Personalizado:**

Para a métrica específica de quantidade de vezes que a página inicial é atualizada, pode ser necessária uma solução personalizada que envolva a utilização de scripts ou APIs personalizados para rastrear interações mais específicas, como atualizações da página inicial, pode ser necessária se as ferramentas padrão não fornecerem esses dados diretamente.

**- Métrica:**
   
     - Quantidade de vezes em que a página inicial é atualizada até um vídeo ser clicado.
  
  **- Configuração Necessária:** Para implementar o rastreamento dessas métricas com software personalizado, será preciso o acesso ao código-fonte do site, para uma compreensão dos eventos de interação do usuário que deseja rastrear e a capacidade de integrar ou desenvolver APIs que possam capturar e transmitir esses dados para sistemas de análise ou armazenamento de dados. 

### Referências

SURAKKA, Sami. Producing a Style Guide in Software Product Development Using the Lean UX Methodology. Tampere: Tampere University of Technology, 2017. Disponível em: https://trepo.tuni.fi/bitstream/handle/123456789/24937/Surakka.pdf?sequence=4&isAllowed=y. 

SANTOSA, Paulus Insap. Measuring User Experience in an Online Store Using Pulse and Heart Metrics. Kursor Journal, [S.l.], v. 7, n. 3, p. 145, out. 2014. ISSN 0216-0544. Disponível em: http://kursorjournal.org/index.php/kursor/article/view/40/33.  

BIG SALAMI. Google’s HEART and GSM user experience planning frameworks. 2021. Disponível em: https://bigsalami.co.uk/insights/google-heart-and-gsm-ux-frameworks/. 

YOUTUBE. Sobre o YouTube. Disponível em: https://about.youtube/. YOUTUBE. Página inicial do YouTube. Disponível em: https://www.youtube.com/. 
