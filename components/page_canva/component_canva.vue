<template>

    <div class="canva">
        <div class="container_canva">
            <div class="escrita_canva">
                <h1>Tags importantes para usar no <label style="color:  #A62177;;">CANVA</label></h1>
            </div>
            <div class="escrita_canva">
                <h2>O QUE É O CANVA?</h2>
                <div class="linha"></div>
                <p>O Canva é uma ferramenta de design feita para criar e editar uma série de artes gráficas a partir de
                    templates prontos: posts para redes sociais, apresentações, logotipos, cartazes e até mesmo vídeos,
                    dentre tantas outras opções. Fontes e imagens também são disponibilizados para as criações.</p>
                <p>Alguns dos motivos de esta ser uma das ferramentas mais utilizadas — tanto por amadores quanto por
                    designers experientes — é o fato de ser fácil de usar e ter uma versão gratuita. </p>
                <p>Além disso, possui uma navegação intuitiva que, em poucos cliques, permite criar designs
                    profissionais.</p>
            </div>

            <div class="escrita_canva">
                <h2>TAGS IMPORTANTES:</h2>
                <div class="linha"></div>
                
            </div>

            <div class="tags_canva">
                <div class="tag">
                    <h2>Tags Gerais</h2>
                    <ul>
                        <li>Design Gráfico</li>
                        <li>Templates (Modelos)</li>
                        <li>Personalização</li>
                        <li>Editor Online</li>
                        <li>Ferramentas de Design</li>
                        <li>Arrastar e Soltar</li>
                        <li>Criação de Conteúdo</li>
                        <li>Publicação de Mídia Social</li>
                    </ul>
                </div>

                <div class="tag">
                    <h2>Tags de Design</h2>
                    <ul>
                        <li>Post para Redes Sociais</li>
                        <li>Apresentação</li>
                        <li>Infográfico</li>
                        <li>Flyer</li>
                        <li>Cartão de Visita</li>
                        <li>Convite</li>
                        <li>Pôster</li>
                        <li>Logotipo</li>
                    </ul>
                </div>

                <div class="tag">
                    <h2>Tags graficas</h2>
                    <ul>
                        <li>Imagens</li>
                        <li>Fotos</li>
                        <li>Ícones</li>
                        <li>Ilustrações</li>
                        <li>Formas</li>
                        <li>Linhas</li>
                        <li>Gráficos</li>
                        <li>Adesivos</li>
                    </ul>
                </div>


            </div>

            <div class="iframe_canva">
                <h2>COMO USAR O CANVA:</h2>
                <div class="linha"></div>
                <iframe src="https://www.youtube.com/embed/Cdkt7qMjgQE?si=bvu5dK5ldLRFmaW3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
            </div>

        </div>
    </div>



</template>

<style>
.linha {
    width: 110px;
    height: 3px;
    margin-left: 10px;
    margin-bottom: 20px;
    border-radius: 10px;
    background-color: #A62177;
}

.canva {
    width: 100%;
    height: auto;
    margin-bottom: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container_canva {
    width: 70%;
    height: 100%;
    display: flex;
    align-items: left;
    justify-content: center;
    flex-direction: column;
}

.escrita_canva {
    width: 600px;
    height: auto;
    margin-bottom: 10px;
    display: flex;
    align-items: left;
    justify-content: center;
    flex-direction: column;
}

.escrita_canva h1 {
    margin-left: 10px;
    font-size: 30px;
}

.escrita_canva h2 {
    margin-left: 10px;
    font-size: 26px;
}

.escrita_canva p {
    margin: 10px;
    color: rgba(43, 43, 43, 0.89)
}

.tags_canva {
    width: 70%;
    height: 300px;
    display: flex;
    margin: 10px;
    flex-wrap: wrap;
}

.tag {
    width:250px;
    height: 250px;
    margin: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: #9FC131;
}

.tag h2 {
    margin-left: 10px;
    font-size: 26px;
    color: rgb(255, 255, 255);
}

.tag ul {
    margin: 10px;
    color: rgba(0, 0, 0, 0.89);
    font-size: 16px;
    list-style: decimal;
    font-weight: bold;
}

.iframe_canva {
    width: 100%;
    height: 350px;
}

.iframe_canva h2 {
    margin-left: 10px;
    font-size: 26px;
}
.iframe_canva iframe {
    margin-left: 10px;
    width: 600px;
    height: 300px;
}


@media screen and (max-width: 800px) {
    .canva {
        width: 100%;
        height: auto;
    }

    .container_canva {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .escrita_canva {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center;
    }

    .escrita_canva h1 {
        margin-top: 100px;
        margin-bottom: 100px;
    }

    .tags_canva {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column
    }

    .iframe_canva {
        width: 100%;
        text-align: center;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .iframe_canva iframe {
        width: 90%;
    }


}
</style>