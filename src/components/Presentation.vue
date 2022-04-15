<template>
<section class="sec-Presentation">
    <h2>Presentation</h2>
    <div class="Presentation">
        <div class="left-pres">
            <p>
                Le but de Petroprotect est d’assurer le fait qu’il y ait le moins de dégâts sur l’environnement causés par les plateformes pétrolières et d’assurer des conseils pour les plateformes en fin de vie. Le démantèlement des plateformes pétrolières coûte cher, est extrêmement polluant à cause de la logistique mis en place pour le va et vient des cargos, les pièces plus petites qui peuvent tomber et les résidus conséquents de pétroles ou de produits chimiques. On donnera les meilleurs solutions pour chaque plateforme, car toutes les plateformes sont différentes et surtout ont un impact différent sur l’écosystème qui l’entoure.
            </p>
        </div>
        <div class="right-pres">
            <img class="down" src="../assets/0e30b22c1ad5a11ea45aeb2113fd1ccb.jpg">
            <img class="up" src="../assets/5d0d91b4a8088bc848212a424c5a4962.jpg">
        </div>
    </div>
</section>
</template>

<style>
.sec-Presentation{
    width: 100%;
    height: 90vh;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: column;
}

.sec-Presentation > h2{
    font-size: 72px;
    color: #406E8E;
}

.Presentation{
    display: flex;
    justify-content:center;
    align-items:center;
    flex-direction:row;
}

.left-pres{
    height: 100%;
    width: 50%;
}

.left-pres > p{
    font-size:27px;
    color: #23395B;
}

.right-pres{
    height: 100%;
    width: 27%;
    position: relative;
    margin-left: 50px;
}

.up{
    width: 376px;
    height: 194px;
    border-radius: 43px;
    border: none;
    position: absolute;
    top: 0;
    right: 0;
    z-index: 10;
    object-fit: cover;
}

.down{
    width: 376px;
    height: 230px;
    border-radius: 60px;
    border: none;
    position: absolute;
    bottom: 0;
    left: 0;
    z-index: 20;
    object-fit: cover;
}
</style>