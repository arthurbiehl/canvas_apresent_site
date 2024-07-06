<template>

    <header>

        <div class="container_header">
            <div class="links_header">
                <img src="../static/logo.jpeg" alt="">

                <a href="#">INÍCIO</a>
                <a href="#sobre">SOBRE</a>
            </div>

            <div class="item_header">
                <a href="#topicos">O QUE É?</a>
            </div>
        </div>

    </header>


</template>

<style>
header {
    width: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    position: absolute;
}

.container_header {
    width: 80%;
    height: 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.container_header img {
    width: 60px;
    height: auto;
}

.links_header {
    width: 100px;
    height: 60px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    margin: 20px;
    transition: 0.5s;
}

.links_header a {
    text-decoration: none;
    font-size: 12px;
    margin: 15px;
    color: black;

}

.links_header a:hover {
    color: rgba(100, 100, 100, 0.767);
}

.item_header {
    width: 200px;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.item_header a {
    width: 150px;
    height: 35px;
    text-decoration: none;
    font-size: 13px;
    color: white;
    background-color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    transition: 0.7s;
    box-shadow: 0px 0px 3px rgba(116, 116, 116, 0.651);
    background-color: #9FC131;
}

.item_header a:hover {
    background-color: #A62177;
    color: white;
}
</style>
