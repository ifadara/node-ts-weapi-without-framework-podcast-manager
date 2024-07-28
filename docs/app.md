# Podcast Manager

### Descrição
Um app ao estilo netflix, aonde possa centralizar difeerentes episódios podcasts separados por categoria

### Domínio

Podcasts feitos em vídeo

#### Features

-  Listar os episódios podcasts em sessões de categorias
    - [saude, fitness, mentalidade, humor]
- Filtrar episódios por nome de podcast

## Como

-  Listar os episódios podcasts em sessões de categorias

### Como vou implementar:
    GET: Retorna lista de episódios


    response:
    '''js
        [
            {
                podcastName: "Flow",
                episode: "CBUM - Flow #319",
                videoId: "pQSuQmUfS30",
                cover: "https://i.ytimg.com/vi/pQSuQmUfS30/hqdefault.jpg",
                link: "https://www.youtube.com/watch?v=pQSuQmUfS30",
                categories: ["saúde", "bodybuilding", "esporte"],
            },
            {
                podcastName: "Flow",
                episode: "RUBENS BARRICHELLO - Flow #339",
                videoId: "4KDGTdiOV4I"
                cover: "https://i.ytimg.com/vi/4KDGTdiOV4I/hq720.jpg",
                link: "https://www.youtube.com/watch?v=4KDGTdiOV4I",
                categories: ["esporte", "corrida"],
            },
        ]
    ''' 
