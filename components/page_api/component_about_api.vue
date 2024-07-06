<template>

    <div class="sobre_api">
        <div class="container_sobre_api">
            <div class="escrita_sobre_api">
                <h2>API de Desenho 2D</h2>
                <div class="linha"></div>
                <p>A Canvas API provê maneiras de desenhar gráficos via JavaScript e via elemento HTML 'Canvas'. Entre
                    outras coisas, ele pode ser utilizado para animação, gráficos de jogos, visualização de dados,
                    manipulação de fotos e processamento de vídeo em tempo real.</p>
            </div>

            <div class="escrita_sobre_api">
                <h2>JavaScript</h2>
                <div class="linha"></div>
                <p>O método Document.getElementById() pega uma referência para o elemento HTML canvas. Em seguida, o
                    método HTMLCanvasElement.getContext() pega o contexto daquele elemento - a coisa sobre a qual o
                    desenho será renderizado.</p>
                <p>O desenho atual é feito usando a interface CanvasRenderingContext2D. A propriedade fillStyle faz o
                    retângulo verde. O método fillRect() coloca seu canto superior direito em (10, 10) e dá a ele o
                    tamanho de 150 unidades de largura e 100 de altura.</p>
            </div>

            <div class="escrita_sobre_api">
                <h2>Exemplo básico</h2>
                <div class="linha"></div>
                <p>Este exemplo simples desenha um retângulo verde para um canvas.</p>
            </div>

            <div class="exemplo_sobre_api">
                <h2><label style="color: orange;">HTML</label></h2>
                <div class="caixa_preta">
                    <p>
                    <pre>&lt;canvas id=&quot;UgCanvas&quot;&gt;&lt;/canvas&gt;</pre>
                    </p>
                </div>
                <h2><label style="color: #FCCB0C;">JAVA SCRIPT</label></h2>
                <div class="caixa_preta">
                    <p>var c=document.getElementById("UgCanvas");<br>
                        var ctx=c.getContext("2d");<br>
                        ctx.fillStyle="#7F7F00";<br>
                        ctx.fillRect(0,0,150,100);</p>
                </div>
            </div>
            <div class="escrita_sobre_api">
                <h2>RESULTADO</h2>
                <div class="linha"></div>
                <div class="caixa_branca">
                    <img src="../../static/retangulo.png" alt="">
                </div>


            </div>

        </div>
    </div>

</template>


<script>



</script>


<style>
.linha {
    width: 100px;
    height: 3px;
    margin-left: 10px;
    margin-bottom: 20px;
    border-radius: 10px;
    background-color: #9FC131;
}

.sobre_api {
    width: 100%;
    height: auto;
    display: flex;
    margin-bottom: 100px;
    justify-content: center;
    align-items: center;
}

.container_sobre_api {
    width: 70%;
    height: 100%;
    margin-top: 100px;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    text-align: left;
    flex-direction: column;
}

.escrita_sobre_api {
    width: 100%;
    height: auto;
    margin: 10px;
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;
}

.escrita_sobre_api h2 {
    margin-left: 10px;
    font-size: 26px;
}

.container_sobre_api p {
    margin: 10px;
    color: rgba(29, 29, 29, 0.856);
    width: 800px
}

.exemplo_sobre_api {
    width: 100%;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;
    margin-left: 20px;
}

.exemplo_sobre_api h2 {
    font-size: 26px;
    margin-bottom: 10px;
    margin-top: 10px
}

/* caixas */

.caixa_preta {
    width: 500px;
    height: auto;
    border-radius: 3px;
    background-color: rgba(37, 37, 37, 0.849);
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;
}

.caixa_preta p {
    color: white;
}

.caixa_preta pre {
    margin-left: 10px;
    color: white;
}

.caixa_branca {
    width: 500px;
    height: 150px;
    margin-left: 10px;
    border-radius: 3px;
    box-shadow: 0px 0px 3px black;
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;
}

.caixa_branca img {
    width: 150px;
    margin: 5px;
}

.caixa_branca p {
    color: white;
}

.caixa_branca pre {
    margin-left: 10px;
    color: white;
}
</style>