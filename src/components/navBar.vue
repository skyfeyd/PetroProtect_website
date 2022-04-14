<template>
    <nav class="nav">
        <div class="nav-logo">
           <img src="../assets/log.png" alt="">
        </div>
        <div class="nav-link">
            <a href="#Presentation">
                <h2>presentation</h2>
            </a>
            <a href="#Team">
                <h2>our team</h2>
            </a>
            <a href="#Contact" class="contactUs-link">
                <h2>contact us</h2>
            </a>
        </div>
    </nav>
</template>

<style>

.nav{
    width: 90%;
    height: 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: row;
    margin: 0 auto;
}

.nav-logo{
    margin-left: -30px;
    height: 100%;
    width: 20%;
    display: flex;
    justify-content: start;
}

.nav-logo > img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}



.nav-link{
    height: 100%;
    width: 50%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.nav-link > a{
    text-decoration: none;
}

.nav-link > a > h2{
    color: #23395B;
    font-weight: 400;   
}

.red{
    width: 30px;
    height: 30px;
    background-color:red;
    display: flex;
}


.contactUs-link{
    width: 228px;
    height: 47px;
    background-color: #8EA8C3;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius:25px;
}


.contactUs-link > h2{
    color: white !important;
    font-weight: 400; 
}

</style>