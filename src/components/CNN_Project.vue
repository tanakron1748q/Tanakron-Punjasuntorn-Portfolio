<template>
    <div class="box">
        <div class="top">
            <img src="/public/CNN_image.png" alt="CNN image" class="CNN_image">
        </div>
        <div class="low">
            <div class="header">
                <p>Emotion Classification using CNN (Happy vs Sad)</p>
            </div>
        </div>
    </div>
</template>

<style scoped>

.box{
    height: 300px;
    width: 500px;
    background-color: red;
}

.top{
    height: 100%;
    width: 100%;    
    background-color: yellow;
}

.low {
    height:70px;
    width: 100%;
    background-color: rgb(217, 207, 199);
}

.low p {
    margin: 0;
}

.header {
    padding-top: 5px;
    margin-left: 5px;
    font-size: 14px;
}

.CNN_image {
    width: 100%;
    height: 100%;
}
</style>