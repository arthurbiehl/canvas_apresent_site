<template>

    <div id="sobre">
        <div class="container_sobre">
            <div class="escrita_sobre">
                <h2>PRA QUE SERVE?</h2>
                <div class="linha"></div>
                <p>A tag canvas em HTML5 é uma área retangular na qual é possível desenhar gráficos e renderizar imagens usando scripts JavaScript. É uma ferramenta fundamental para desenvolvedores web que desejam criar gráficos e animações interativas diretamente no navegador, proporcionando flexibilidade, desempenho e controle sobre elementos visuais na web.</p>
                <p>Canva é uma plataforma online que permite criar designs gráficos de maneira intuitiva e acessível, sem exigir habilidades avançadas em design gráfico.</p>
                <p>É amplamente utilizada por indivíduos e empresas para criar uma variedade de conteúdos visuais, como posts para redes sociais, apresentações, cartões, pôsteres, currículos, convites e muito mais.</p>
            </div>

            <div class="item_sobre">
                <img src="../static/sobre.jpeg" alt="">
            </div>
        </div>
    </div>



</template>

<style>

.linha {
    width: 100px;
    height: 3px;
    margin-left: 10px;
    margin-bottom: 20px;
    border-radius: 10px;
    background-color: #A62177;
}

#sobre{
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container_sobre {
    width: 70%;
    height: 500px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.escrita_sobre {
    width: 900px;
    height: 400px;
}

.escrita_sobre h2 {
    margin-left: 10px;
    font-size: 26px;
}

.escrita_sobre p {
    margin: 10px;
    color: rgba(65, 65, 65, 0.705)
}

.item_sobre {
    width: 200px;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.item_sobre img {
    width: 300px;
}


</style>