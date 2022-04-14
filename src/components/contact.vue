<template>
    <section class="contact-sec">
        <h2>Contact us</h2>
        <div class="contacts">
            <div class="right-contact">
                <img src="../assets/Component1.png" alt="">
            </div>
            <div class="left-contact">
                <form>
                    <div class="form-name">
                        <img class="name" src="../assets/Frame2.png" alt="">
                        <input placeholder="name">
                    </div>
                    <div class="form-mail">
                        <img class="mail" src="../assets/Frame1.png" alt="">
                        <input placeholder="email">
                    </div>
                    <div class="form-message">
                        <textarea class="message" placeholder="message"></textarea>
                    </div>
                    <button>Send</button>
                </form>
            </div>
        </div>
    </section>
</template>

<style>
.contact-sec{
    height: 100vh;
    width: 100%;
    margin-top: 200px;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: column;
}

.contact-sec > h2{
    font-size: 72px;
    color: #406E8E;
}

.contacts{
    width: 100%;
    display: flex;
    justify-content:center;
    align-items:center;
    flex-direction: row;
}

.right-contact{
    width: 50%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}

.right-contact > img{
    width: 70%;
    height: 70%;
    object-fit: contain;
}
.left-contact{
    width: 50%;
    height: 100%;
}

form{
    width: 60%;
    height: 100%;
    display: flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
}

.form-name{
    width: 100%;
    height: 97px;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: row;
    position: relative;
    margin-bottom: 20px;
}

.name{
    width: 39px;
    height: 45px;   
    position: absolute;
    left: 35px;
}

.form-mail{
    width: 100%;
    height: 97px;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: row;
    position: relative;
    
    
}
.mail{
    width: 39px;
    height: 39px;
    position: absolute;
    left: 35px;
}

.left-contact > form > div > input, textarea{
    width: 100%;
    height: 100%;
    background: #C4C4C4;
    border-radius: 52px;
    display: flex;
    justify-content: start;
    align-items: start;
    border: none;
    margin: 20px;
    padding-left: 60px; 
    resize: none;
    font-family: poppins;
    font-size: 26px;
}


.form-message {
    width: 100%;
    height: 218px;
    display: flex;
    justify-content: start;
    align-items: center;
    flex-direction: row;
    position: relative;
    margin-top: 20px;
}

.left-contact > form > .form-message > .message{
    height: 100%;
    width: 100%;
    text-align: justify;
    padding-top: 20px;
    padding-left: 20px;
}

.left-contact > form > button{
    width: 95%;
    height: 85px;
    display: flex;
    justify-content:center;
    align-items:center;
    background: #406E8E;
    border-radius: 52px;
    border: none;
    color: white;
    font-family: poppins;
    font-size: 26px;
    margin-top: 20px;
}

</style>