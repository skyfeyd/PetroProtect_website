<template>
<section class="sec-Presentation">
    <h2>Presentation</h2>
    <div class="Presentation">
        <div class="left-pres">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce non venenatis nisl. Nunc ac dapibus ex. Integer ante nisi, luctus sollicitudin nulla sed, consectetur hendrerit diam. Vivamus nec justo at sem elementum pharetra nec sit amet mauris. Aenean dui metus, sollicitudin eget pretium et, vulputate in tellus. Sed vitae hendrerit tellus. Curabitur ut ipsum odio. Praesent sed ex a est egestas ornare at vehicula elit. Mauris ac est malesuada, pretium metus non, varius purus.

            </p>
        </div>
        <div class="right-pres">
            <span class="down"></span>
            <span class="up"></span>
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
    background-color: #E28989;
    border-radius: 43px;
    border: none;
    position: absolute;
    top: 0;
    right: 0;
    z-index: 10;
}

.down{
    width: 376px;
    height: 230px;
    background-color: #50B9F3;
    border-radius: 60px;
    border: none;
    position: absolute;
    bottom: 0;
    left: 0;
    z-index: 20;
}
</style>