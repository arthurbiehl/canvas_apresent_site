<template>


    <a href="/api_page">
        <div class="card1">
            <img src="../static/image1.png" alt="">
            <div class="container_card">
                <h1><label style="color: #9FC131;">Desenho 2D CANVAS</label></h1>
            </div>
        </div>
    </a>

    <a href="/canva_page">
        <div class="card2">
            <img src="../static/image2.png" alt="">
            <div class="container_card">
                <h1><label style="color: #A62177;">Como usar o CANVA?</label></h1>
            </div>
        </div>
    </a>

    <a href="/praticas_page">
        <div class="card3">
            <img src="../static/image3.png" alt="">
            <div class="container_card">
                <h1><label style="color: #9FC131;">Propriedades CANVAS</label></h1>
            </div>
        </div>
    </a>

    <a href="">
        <div class="card4">
            <img src="../static/image4.png" alt="">
            <div class="container_card">
                <h1><label style="color: #A62177;">Integração com outras Tecnologias</label></h1>
            </div>
        </div>
    </a>

</template>

<script setup>

</script>

<style>
a {
    text-decoration: none;
    color: white;
    font-weight: 300;
}

.card1 {
    width: 250px;
    height: 300px;
    margin: 10px;
    border-radius: 5px;
    display: flex;
    justify-content: flex-end;
    align-items: left;
    flex-direction: column;
    background-color: red;
    filter: blur(1.5px);
    transition: 0.5s;
    background: url('');
}

.card1:hover {
    filter: blur(0px);

}

.card2 {
    width: 250px;
    height: 300px;
    margin: 10px;
    border-radius: 5px;
    display: flex;
    justify-content: flex-end;
    align-items: left;
    flex-direction: column;
    background-color: red;
    filter: blur(1.5px);
    transition: 0.5s;
    background: url('');
}

.card2:hover {
    filter: blur(0px);

}

.card3 {
    width: 250px;
    height: 300px;
    margin: 10px;
    border-radius: 5px;
    display: flex;
    justify-content: flex-end;
    align-items: left;
    flex-direction: column;
    background-color: red;
    filter: blur(1.5px);
    transition: 0.5s;
    background: url('');
}

.card3:hover {
    filter: blur(0px);

}

.card4 {
    width: 250px;
    height: 300px;
    margin: 10px;
    border-radius: 5px;
    display: flex;
    justify-content: flex-end;
    align-items: left;
    flex-direction: column;
    background-color: red;
    filter: blur(1.5px);
    transition: 0.5s;
    background: url('');
}

.card4:hover {
    filter: blur(0px);

}

.container_card {
    width: 100%;
    height: 55px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.container_card h1 {
    font-size: 20px;
    color: rgba(20, 20, 20, 0.747);
}
</style>
