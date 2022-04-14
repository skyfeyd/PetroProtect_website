<template>
    <footer>
        <div class="footer-left">
            <img src="../assets/log.png" alt="">
        </div>
        <div class="footer-right">
            <div class="plan">
                <h2>Plan du site</h2>
                <a href="#Main"><p>Homepage</p></a>
                <a href="#Presentation"><p>Presentation</p></a>
                <a href="#Team"><p>Team</p></a>
                <a href="#Contact"><p>Contact</p></a>
            </div>

            <div class="Address">
                <h2>Address:</h2>
                <p>78 rue du moulin <br> 98677 Brest</p>
            </div>
            <div class="Phone">
                <h2>Phone:</h2>
                <p>07 65 45 13 98</p>
            </div>
        </div>
    </footer>
</template>


<style>
footer{
    height: 280px;
    width: 100%;
    background-color: #CBF7ED;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: row;
    margin-top: 100px;
}

.footer-left {
    width: 20%;
    height: 100%;
}

.footer-right {
    width: 70%;
    height: 100%;
    display: flex;
    justify-content: space-around;
    flex-direction: row;
}

.footer-right > div > h2{
    font-weight: 400;
    font-size: 27px;
    color: #406E8E;
}

.footer-right > div > a{
    text-decoration: none;
    color: #406E8E;
}

.footer-right > div > p{
    font-weight: 400;
    font-size: 24px;
    color: #406E8E;
}

</style>