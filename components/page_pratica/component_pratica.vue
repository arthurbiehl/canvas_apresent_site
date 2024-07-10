<template>

    <div class="pratica">
        <div class="container_pratica">
            <div class="escrita_pratica">
                <h1>Propriedades Do Canvas:</h1>
                <div class="linha"></div>
            </div>
            <div class="tags_pratica">
                <div class="card_pratica">
                    <h2>Propriedades do Contexto 2D</h2>
                    <p><label style="font-weight: bold;">canvas:</label> refere-se ao elemento</p>
                    <p><label style="font-weight: bold;">fillStyle:</label>  cor ou estilo para preencher formas desenhadas.</p>
                    <p><label style="font-weight: bold;">strokeStyle:</label>   cor ou estilo para traços.</p>
                    <p><label style="font-weight: bold;">lineWidth: </label>  largura da linha.</p>
                    <p><label style="font-weight: bold;">font:</label>   fonte usada para o texto.</p>
                    <p><label style="font-weight: bold;">textAlign:</label>   alinhamento horizontal do texto.</p>
                    <p><label style="font-weight: bold;">textBaseline:</label>   alinhamento vertical do texto.</p>

                    <h2>Estado do Canvas</h2>
                    <p><label style="font-weight: bold;">save():</label> salva o estado atual do canvas.</p>
                    <p><label style="font-weight: bold;">restore():  </label>  restaura o estado salvo mais recentemente.</p>


                </div>
                <div class="card_pratica">
                    <h2>Métodos de Desenho de Caminho</h2>
                    <p><label style="font-weight: bold;">beginPath():</label> inicia um novo caminho.</p>
                    <p><label style="font-weight: bold;">closePath()</label>  : fecha o caminho atual.</p>
                    <p><label style="font-weight: bold;">moveTo(x, y):</label>   move o ponto de início do caminho para (x, y).</p>
                    <p><label style="font-weight: bold;">lineTo(x, y): </label>  desenha uma linha até (x, y).</p>
                    <p><label style="font-weight: bold;">arc(x, y, radius, startAngle, endAngle, anticlockwise):</label>   desenha um arco.</p>
                    <p><label style="font-weight: bold;">rect(x, y, width, height):</label>   desenha um retângulo.</p>
                    <p><label style="font-weight: bold;">fill()</label>   preenche o caminho atual.</p>
                    <p><label style="font-weight: bold;">stroke(): </label>    desenha o contorno do caminho atual.</p>
                </div>
                <div class="card_pratica">
                    <h2>Métodos de Desenho de Retângulos</h2>
                    <p><label style="font-weight: bold;">fillRect(x, y, width, height): </label> desenha um retângulo preenchido.</p>
                    <p><label style="font-weight: bold;">strokeRect(x, y, width, height): </label> desenha o contorno de um retângulo.</p>
                    <p><label style="font-weight: bold;">clearRect(x, y, width, height):</label>   limpa a área do retângulo especificado.</p> 

                    <h2>Transformações</h2>

                    <p><label style="font-weight: bold;">translate(x, y): </label> move a origem do canvas.</p>
                    <p><label style="font-weight: bold;">rotate(angle): </label>  rotaciona o canvas.</p>
                    <p><label style="font-weight: bold;">scale(x, y): </label>   escala o canvas.</p>
                    <p><label style="font-weight: bold;">transform(a, b, c, d, e, f): </label>    aplica uma transformação matricial.</p>
                    <p><label style="font-weight: bold;">setTransform(a, b, c, d, e, f): </label> redefine a transformação matricial.</p>
                </div>
                <div class="card_pratica">
                    <h2>Métodos de Desenho de Texto</h2>
                    <p><label style="font-weight: bold;">fillText(text, x, y, maxWidth): </label> desenha texto preenchido.</p>
                    <p><label style="font-weight: bold;">strokeText(text, x, y, maxWidth): </label> desenha o contorno do texto.</p>
                    <p><label style="font-weight: bold;">measureText(text): </label> retorna a largura do texto.</p>
                    <h2>Métodos de Manipulação de Imagens</h2>
                    <p><label style="font-weight: bold;">drawImage(image, dx, dy): </label>  desenha uma imagem.</p>
                    <p><label style="font-weight: bold;">drawImage(image, dx, dy, dWidth, dHeight): </label> desenha uma imagem escalada.</p>
                    <p><label style="font-weight: bold;">drawImage(image, sx, sy, sWidth, sHeight, dx, dy, dWidth, dHeight): </label> desenha uma porção da imagem.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style>
.linha {
    width: 200px;
    height: 3px;
    margin-left: 10px;
    margin-bottom: 50px;
    border-radius: 10px;
    background-color: #9FC131;
}

.pratica {
    width: 100%;
    height: auto;
    margin-bottom: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
}

.container_pratica {
    width: 70%;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.escrita_pratica {
    width: 100%;
    height: 100px;
    margin: 10px;
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;

}

.container_pratica h1 {
    margin-left: 10px;
    font-size: 30px;
}

.tags_pratica {
    width: 840px;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-wrap: wrap;
}

.card_pratica {
    width: 400px;
    height: 450px;
    margin: 10px;
    padding: 10px;
    display: flex;
    justify-content: flex-start;
    align-items: left;
    border-radius: 2px;
    flex-direction: column ;
    background-color: rgba(34, 34, 34, 0.781);
}

.card_pratica h2 {
    margin: 10px;
    font-size: 22px;
    font-weight: 500;
    color: rgb(255, 255, 255);
}

.card_pratica p {
    margin-left: 10px;
    margin-bottom: 5px;
    font-size: 17px;
    color: rgb(247, 247, 247);
}

@media screen and (max-width: 800px)  {
    .pratica {
        width: 100%;
        height: auto;
    }

    .container_pratica {
        width: 100%;
        height: auto;
    }

    .escrita_pratica {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        text-align: center
    }

    .tags_pratica {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }

    .card_pratica {
        width: 100%;
        margin: 0px;
        border-radius: 0px;
        margin-bottom: 10px
    }
}
</style>