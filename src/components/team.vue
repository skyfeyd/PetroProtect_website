<template>
    <section class="team-sec">
        <h2>Our team</h2>
        <div class="cards">
            <div class="card-team">
                <img src="../assets/fffd17cac14835df1f59a2c19c4c2bff.png" alt="">
                <h4>Louis Gauthier</h4>
            </div>
            <div class="card-team">
                <img src="../assets/e95a647a98ed9f5e377b34e0fd53b7a2.jpg" alt="">
                <h4>Manon Gardin</h4>
            </div>
            <div class="card-team">
                <img src="../assets/46b187ac584cdfe4f50f49c719611a06.jpg" alt="">
                <h4>Lola Chareyre Thouret</h4>
            </div>
            <div class="card-team">
                <img src="../assets/449fec33770eba5106df5d37a91e0dfa.jpg" alt="">
                <h4>Titouan Butot</h4>
            </div>
            <div class="card-team">
                <img src="../assets/IMG_0118.jpg" alt="">
                <h4>Raphaël Castelnau</h4>
            </div>
            <div class="card-team">
                <img src="../assets/31b9915ef9728353c9a119f818a592f4.jpg" alt="">
                <h4>Christophe Zheng</h4>
            </div>
        </div>
    </section>
</template>


<style>
.team-sec{
    height: 100vh;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.team-sec > h2{
    font-size: 72px;
    color: #406E8E;
}

.cards{
    width: 70%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
    flex-wrap: wrap;
    
}
.card-team{
    width: 264px;
    height: 394px;
    position: relative;
    margin: 38px;
    display: flex;
    justify-content: end;
    align-items: center;
    flex-direction: column;
    border-radius: 56px;
    background-color: black;
}

.card-team > img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 56px;
    opacity: 65%;
    transition: 300ms ease-in-out;
}

.card-team > h4{
    opacity: 0;
    position: absolute;
    color: white;
    transition: 300ms ease-in-out;
}

.card-team:hover > img{
    opacity: 1;
}


.card-team:hover > h4{
    opacity: 1;
}

</style>