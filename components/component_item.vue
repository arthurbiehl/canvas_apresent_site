<template>

    <div id="topicos">

        <div class="container_topicos">
            <h2>O QUE É O <label>CANVAS</label>?</h2>
            <div class="linha"></div>
            <div class="items_topicos">
                <ComponentItemCard />
            </div>

        </div>
    </div>


</template>

<style>
label {
    color: #9FC131;
}

.linha {
    width: 130px;
    height: 3px;
    margin-left: 10px;
    margin-bottom: 20px;
    border-radius: 10px;
    background-color: #9FC131;
}

#topicos {
    width: 100%;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    text-align: left;
}

.container_topicos {
    width: 80%;
    height: 500px;
    display: flex;
    justify-content: flex-start;
    align-items: left;
    flex-direction: column;
    flex-wrap: wrap;
}

.container_topicos h2 {
    margin-left: 10px;
    text-align: left;
    font-size: 26px;
}

.items_topicos {
    width: 100%;
    height: 300px;
    display: flex;
    justify-content: center;
    align-items: center;
}

@media screen and (max-width: 800px) {
    #topicos {
        width: 100%;
        height: auto;
        margin-top: 20px;
        margin-bottom: 20px;
    }

    .container_topicos {
        width: 100%;
        height: auto;
        margin-top: 100px;
        margin-bottom: 100px;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .items_topicos {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
}
</style>