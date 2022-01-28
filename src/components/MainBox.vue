<template>
    <main>
        <div class="ms_container">
            <div v-for="(card, index) in comicsList" :key="index"
                class="ms_comics-card">
                <div class="ms_card-image">
                    <img :src="card.thumb" :alt="card.series">
                </div>
                <p>{{card.series.toUpperCase()}}</p>
            </div>
        </div>
    </main>
</template>

<script>
export default {
    props: {
        comicsList: Array
    }
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

    main {
        background-color: #222;
        color: $white-color;
        padding: 30px 0;

        .ms_container {
            width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            flex-wrap: wrap;

            .ms_comics-card {
                width: calc((100% - 150px) / 6);

                .ms_card-image {
                    height: 180px;
                    overflow: hidden;
                }

                p {
                    margin: 20px 0 30px;
                }
            }
        }
    }
</style>