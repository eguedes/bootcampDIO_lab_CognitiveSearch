# bootcampDIO_lab_CognitiveSearch

## Laboratório: Azure Cognitive Search: Utilizando AI Search para indexação e consulta de Dados

Este repositório tem como objetivo entregar o projeto final do módulo "Inteligência de Documentos e Mineração de Conhecimento" do Bootcamp "Microsoft Azure AI Fundamentals" da DIO, ministrado pela Valéria Baptista.

Neste exercício, foi criado um recurso Azure AI servcies, um AI Search e uma Storage account. 

Em seguida, tambem foi criado um contêiner. Para uso no laboratório, este contâiner é configurado com nível de acesso Público. Para obter um volume de dados que pudesse ser usado para realizar testes, foram importados arquivos de exemplo, disponíbilizados [no tutorial da Microsoft](https://aka.ms/mslearn-coffee-reviews).

Após o upload dos arquivos de exemplo, eles podem ser usados no Azure AI Search para se obter *insights*. Para isso, eles são importados para o recurso AI Search. Na importação são selecionadas skills cognitivas, funções que permitem a extração de nomes de lugares, frases chave, sentimento, e tags e imagens de imagens. Para a extração de informações de imagens, também foi habilitado o OCR.

### Cognitive Search

Com tudo configurado, é possível usar o Search explorer para fazer testes de buscar e revisar os resultados.

Na importação dos dados também foi criada uma knowledge store. Na knowledge store se encontram dados extraídos enriquecidos pelas skills AI no formato de projeções e tabelas.

Num mundo onde estamos sobrecarregados de dados (que podem ou não ser transformados em informações), é de grande relevância ter uma ferramenta que faça uma análise dos dados de forma que eles possam ser pesquisados e oferecer insights em diferentes frentes e abordagens. A capacidade de obtenção de informações de imagens se apresenta como outra grande vantagem, visto que grande parte do volume de dados trafegados hoje são de conteúdo audio-visual. 
