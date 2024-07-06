<template>

    <div class="cover">
        <div class="container_cover">
            <div class="escrita_cover">
                <h1><label style="color: #9FC131;">CANVAS</label> e <label style="color: #A62177;">CANVA</label></h1>
                <p>Criações de graficos e formas.</p>
            </div>

            <img src="../static/logo.jpeg" alt="">
        </div>
    </div>


</template>

<style>

.cover {
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: url('../static/fundo.jpeg');
    background-size: auto;
}

.container_cover {
    width: 90%;
    height: 500px;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.escrita_cover {
    width: 350px;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: left;
    flex-direction: column;
    text-align: left;
}

.escrita_cover h1 {
    margin-bottom: 10px;
    font-size: 35px;
}

.escrita_cover p {
    font-size: 15px;
    color: rgba(136, 136, 136, 0.863);
}


</style>
