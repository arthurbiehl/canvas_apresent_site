<template>

    <div class="interacao">
        <div class="container_interacao">

            <div class="escrita_interacao">

                <div class="escrita">
                    <h1>Por que as empresas de tecnologia escolhem o Canva</h1>
                    <div class="linha"></div>
                    <p>Desenvolver o marketing de uma empresa de tecnologia, do início do negócio à sua expansão, exige
                        muito mais do que apenas encontrar e concretizar oportunidades de negócios. Um marketing eficaz
                        é aquele que consegue construir uma marca memorável, deixar uma primeira impressão duradoura e
                        criar conteúdo informativo que agrade a comunidade. É aí que o Canva entra. Nossa plataforma
                        permite que qualquer pessoa da sua equipe crie conteúdo relevante e com a identidade visual da
                        marca, em qualquer formato.</p>

                    <div class="icones">
                        <h2>Biblioteca de recursos</h2>
                        <div class="icone">
                            <icon name="ph:google-photos-logo" class="contact_icon" />

                            <p>Escolha entre mais de 100 milhões de imagens e elementos de design premium e grátis.</p>
                        </div>

                        <h2>Colaboração em tempo real</h2>
                        <div class="icone">
                            <icon name="ph:circle-wavy-question-fill" class="contact_icon" />

                            <p>A equipe pode criar, editar e ver na hora as alterações nos designs.</p>
                        </div>



                    </div>
                </div>

                <div class="image_interacao">
                    <img src="../../static/canva1.jpeg" alt="">
                </div>
            </div>


            <div class="escrita_interacao">

                <div class="image_interacao">
                    <img src="../../static/canva2.jpeg" alt="">
                </div>

                <div class="escrita">
                    <h1>Proteja a identidade da sua marca</h1>
                    <div class="linha"></div>
                    <p>De infográficos para apresentar um novo produto ou recurso de software a vídeos para promover a cultura ou a visão da empresa, garanta a uniformidade visual da sua marca usando o Canva para criar seu conteúdo..</p>

                    <div class="icones">
                        <h2>Kit de Marca</h2>
                        <div class="icone">
                            <icon name="ph:money-wavy" class="contact_icon" />

                            <p>Crie ou faça upload dos elementos da marca para garantir a unidade visual.</p>
                        </div>

                        <h2>Elementos bloqueados</h2>
                        <div class="icone">
                            <icon name="ph:lock-key-fill" class="contact_icon" />

                            <p>Bloqueie os elementos importantes nos modelos de design para manter a uniformidade.</p>
                        </div>

                        <h2>Fluxo de trabalho de aprovação</h2>
                        <div class="icone">
                            <icon name="ph:check" class="contact_icon" />

                            <p>Revise e aprove designs em tempo real.</p>
                        </div>

                    </div>
                </div>


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

.interacao {
    width: 100%;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.container_interacao {
    width: 70%;
    height: auto;
    margin-top: 50px;
    margin-bottom: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column
}

.escrita_interacao {
    width: 100%;
    height: auto;
    display: flex;
    justify-content: center;
    align-items: flex-start;
}

.escrita {
    width: 50%;
    height: 500px;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: left;
    flex-direction: column;
}

.escrita h1 {
    font-size: 30px;
    font-weight: 500;
    margin-left: 10px;
}

.escrita p {
    margin-left: 10px;
}

.image_interacao img {
    width: 600px;
    padding: 20px;
}

.icones {
    width: auto;
    height: auto;
    margin: 10px;
    display: flex;
    justify-content: left;
    align-items: left;
    flex-direction: column;
}

.icones h2 {
    font-size: 20px;
}

.icone {
    width: 600px;
    display: flex;
    justify-content: left;
    align-items: center;
    margin: 10px
}

.contact_icon {
    font-size: 25px;
}
</style>