

**A network analysis of rumination on loneliness and the relationship with depression** - Nature Mental Health(https://doi.org/10.1038/s44220-024-00350-x) 

Autores: [[Jingyi Luo]], [[Nichol M. L. Wong]],  [[Ruibin Zhang]], [[Jingsong Wu]], [[Robin Shao]], [[Chetwyn C. H. Chan]], [[Tatia M. C. Lee]]

Tipo: artigo original / experimental / survey

keywords: [[Depressão]], [[Solidão]], [[network analysis]], [[ruminação de sentimento]]


******

Objetivos:

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=2&selection=99,0,103,63&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.47]]
> > the present study will take a first step to examine the relationship between specific loneliness items, rumination items and individual depressive symptoms
> 
> 



Metodologia:

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=2&selection=104,6,104,60&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.47]]
> > a network analysis approach in a cross-sectional study

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=3&selection=12,31,18,45&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.48]]
> > First, we aim to establish the relationship between loneliness, rumination and depression using their total scores to confirm the mediation effects of rumination, in line with previous research. Second, to achieve a more in-depth understanding of the relationship, we will construct a network of loneliness and depressive symptoms and a network of loneliness, rumination and depressive symptoms using more specific items
> 
> 

> Uma amostra de 904 adultos participantes foram recrutados nas cidades de Hong Kong, Guangzhou and Fuzhou (China), durante a pandemia (mais especificamente no período entre 2021-2023). Montreal Cognitive Assessment  (MoCA)foi utilizado para selecionar os participantes; aqueles que tivessem o score abaixo de 22 eram automaticamente eliminados. Essa seleção visava retirar a população idosa da análise.
> 
> **Os questionários**
> 
> Os questionarios incluiam medidas como solidão, ruminação, depressão, características demográficas e outras qualidades individuais.
> Solidão foi medida através da [UCLA Loneliness Scale version 3 ](obsidian://open?vault=Pesquisa%20Cient%C3%ADfica&file=Pesquisa-Cient-fica---Reposit-rio%2FArtigos%2FRefer%C3%AAncias%2FFerramentas%2FUCLA%20Loliness%20assetment.pdf) 
> Ruminação foi medida através do [22-items RRS](obsidian://open?vault=Pesquisa%20Cient%C3%ADfica&file=Pesquisa-Cient-fica---Reposit-rio%2FArtigos%2FRefer%C3%AAncias%2FFerramentas%2F22-item%20RRS.pdf), variado da [Teoria da Rsposta de Estilos](), de Nolen-Hoeksema
> Depressão foi medido através do [PHQ-9](obsidian://open?vault=Pesquisa%20Cient%C3%ADfica&file=Pesquisa-Cient-fica---Reposit-rio%2FArtigos%2FRefer%C3%AAncias%2FFerramentas%2FPHQ-9.pdf).
> 
> **Análise de dados**
> 
>  Foi utilizado correlações de coeficientes de Spearman para associar as variáveis já dispostas. Em seguida, um "mediation model" entre elas foi disposto; solidão era um termo independente, ruminação era o termo mediante e depressão o termo dependente. Para verificação, foi realizado substituição tipo Bootstrap.
>  Em seguida, foi realizado uma análise do tipo network, usando os algoritmos LASSO e EBIC (ferramentas do [bootnet packge](obsidian://open?vault=Pesquisa%20Cient%C3%ADfica&file=Pesquisa-Cient-fica---Reposit-rio%2FArtigos%2FRefer%C3%AAncias%2FNetwork%20Science%2FEstimating%20psychological%20networks%20and%20their%20accuracy%3A%20A%20tutorial%20paper.pdf)), e a centralidade através de ferramentas disponibilizadas no [qgraph packge](obsidian://open?vault=Pesquisa%20Cient%C3%ADfica&file=Pesquisa-Cient-fica---Reposit-rio%2FArtigos%2FRefer%C3%AAncias%2FNetwork%20Science%2Fqgraph%3A%20Network%20Visualizations%20of%20Relationships%20in%20Psychometric%20Data.pdf). a robustez da rede foi testada através de métodos bootstrap.
>  Para a ilustração da rede, foi utilizado o conjunto de ferramentas do [network package](https://cran.r-project.org/package=networktools "https://cran.r-project.org/package=networktools"). 



Resultados:

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=3&selection=49,0,50,66&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.48]]
> > Spearman’s correlations suggest that loneliness, rumination and depression are significantly positively correlated with each other

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=4&selection=128,0,134,69&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.49]]
> > Our two major hypotheses were satisfied by the study. First, in the mediation model, rumination indeed mediated the relationship between loneliness and depression. Our second hypothesis was also satisfied. In the loneliness–depression network, the present study did not reveal stable bridge symptoms due to the poor reliability of the bridge centrality indices. The instability of the loneliness–depression only network means that the two constructs are not the whole picture.
> 
> 

> A amostra final foi de 900 adultos.
> O modelo de mediação foi realizado, com a solidão tendo efeito significativo na depressão e ruminação, e por sua vez a ruminação associada a depresão; ruminação media a relação solidão-depressão

![[Pasted image 20260102184753.png]]

> A seguinte pergunta representa a conexão entre os questionários e suas relações:

![[Pasted image 20260102185258.png]]

> Relações mais comuns:
> > 1) D7 foi a ponte entre os aglomerados solidão depressão ("dificuldade em se concentrar nas coisas")
> > 2) D7 se conecta fortemente com L11 ("com que frequência você se sente sozinho?")
> > 3) As pontes entre solidão e depressão são instáveis (análise bootstrap)
> > 4) a ponte que liga mais fortemente os três aglomerados é L4
> > 5) L4 se conecta fortemente com R1, e vice versa
> 
> Um padrão simples e que explica a relação entre as variáveis é que no gráfico onde as três variáveis são dispostas, vértices da solidão se ligavam predominantemente à vértices da ruminação, que por sua vez ligavam-se predominantemente com vértices da depressão, dispondo a ruminação como intermediador efetivo das duas variáveis.
>


Síntese de conclusões:

> [!PDF|red] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=4&selection=137,26,141,30&color=red|A network analysis of rumination on loneliness and the relationship with depression, p.49]]
> > in the present study, the loneliness–depression network indicated that the activation of the loneliness community alone is not stably associated with the manifestation of specific depressive symptoms. 
> 
> 

> Na rede solidão-ruminação-depressão, a principal ponte entre elementos foi o termo L4, de pergunta "você se sente frequentemente sozinho?", e R1, "ruminação da solidão".

> [!PDF|important] [[Pesquisa-Cient-fica---Reposit-rio/Fichamentos/Versões em PDF/A network analysis of rumination on loneliness and the relationship with depression.pdf#page=4&selection=162,34,171,53&color=important| A hipótese da ruminação]]
> > In our study, the maladaptive way of coping with the stressor—in this case, ruminating on the loneliness feelings—can be the reason why loneliness can result in the development of further depressive symptoms. Especially during the pandemic, due to the Chinese government’s compulsory implementation of social distancing policies, people had less chance to gather with their socially significant others and form or maintain their social bonds in person. Social activities are especially important for younger adults (the primary participants of the present study), who require a larger amount of social connection with their friends and colleague



informações adicionais:

> Este artigo se trata de uma pesquisa que utiliza-se do *framework* de análise em "network", frequente em trabalhos de cunho psicológico que visam estabelecer relações causais entre variáveis em várias dimensões do indivíduo.
> 
> Leia os artigos a seguir para compreender melhor esse *framework*:
> [[Network analysis of multivariate data in psychological science.pdf]]
> [[Network analysis a brief overview and tutorial.pdf]]
> 
> material suplementar do artigo: [[supplementar content - A network analysis of rumination on loneliness and the relationship with depression.pdf]] 




Referência ABNT: LUO, J. et al. A network analysis of rumination on loneliness and the relationship with depression. **Nature Mental Health**, 19 dez. 2024.


Referência Vancouver: Luo J, Nichol, Zhang R, Wu J, Shao R, Chan, et al. A network analysis of rumination on loneliness and the relationship with depression. Nature Mental Health. 2024 Dec 19;

‌