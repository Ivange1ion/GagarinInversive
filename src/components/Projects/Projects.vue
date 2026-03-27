<script setup>
    import Button from "../UI/Button.vue";
</script>

<template>
    <div id="projects">
        <div class="part_head">
            Другие проекты
        </div>
        <div class="text-item">
            У нашей компании имеется успешный опыт в разработке коммерческих продуктов виртуальной реальности!
        </div>
        <div id="projects-cards">
            <div class="card">
                <img class="project-img" src="../../assets/img/blood.svg" alt="">
                <div class="card-text">
                    <div class="card-head text-item">Сердечно-соссудистая система</div>
                    <hr>
                    <div class="text-item">Станьте клеткой внутри организма, исследуйте его изнутри</div>
                    <!-- <Button class="detail">Подробнее</Button> -->
                     <button class="detail">Подробнее</button>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .detail{
        font-size: 25px;
        font-weight: bold;
        width: 70%;
        background-color: #ff8d28;
        color: black;
        border-radius: 60px;
        text-align: center;
        padding: 15px;
        position: relative;
        left: 15%;
        bottom: 0;
    }
    .project-img{
        width: 30%;
        height: 100%;
    }
    .card{
        display: flex;
        justify-content: space-between;
        margin: 40px;
    }
    .card-head{
        color: var(--text-span);
    }
    .card-text{
        width: 60%;
    }
</style>
