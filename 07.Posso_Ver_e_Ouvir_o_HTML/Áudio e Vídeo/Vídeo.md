# Vídeos

    - src
    - controls
    - se não funcionar ?
        * fallback content

    - source  
        * src
        * type

    - sobre serviços de terceiros

```HTML
<video src="link local" controls></video>
```
```HTML
<video controls
    width="500" largura
    height="400" altura
    autoplay
    preload="metadata"
    loop
    muted
    poster="link da imagem"
>
    <!-- autoplay - inicia o video assim que a pagina carregar -->
    <!-- preload (none ou metadata)- começa a fazer a leitura do video -->
    <!-- loop - quando o video acabar ele inicia novamente -->
    <!-- muted - deixa o video mutado -->
    <!-- poster - deixa uma imagem no video até que ele seja iniciado -->

    <source src="link local"
    type="video/mp4">
</video>
```