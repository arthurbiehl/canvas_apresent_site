<template>

    <footer>
        <div class="container_footer">
            <img src="../static/logo.jpeg" alt="">
            <div class="links_footer">
                <h2>LINKS UTEIS</h2>
                <a href="">INÍCIO</a>
                <a href="">SOBRE</a>
                <a href="">O QUE É?</a>
            </div>
        </div>

        <div class="feito_por">
            <p>FEITO POR ARTHUR BIEHL, ANNA, FLÁVIA</p>
        </div>

    </footer>
    

</template>

<style>

footer {
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: left;
    align-items: left;
    flex-direction: column;
    box-shadow: 0px 0px 2px rgba(158, 158, 158, 0.671);
}

.container_footer {
    width: 600px;
    height: 300px;
    margin: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container_footer img {
    width: 150px;
}

.links_footer {
    width: 200px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: flex-start;
    flex-direction: column;
}

.links_footer a {
    color: rgb(53, 53, 53);
    transition: 0.5s;
    font-weight: 600;
}

.links_footer h2 {
    font-size: 17px;
    font-weight: bold;
}

.links_footer a:hover {
    color: rgba(95, 95, 95, 0.767)
}

.feito_por {
    width: 100%;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold
}




</style>



