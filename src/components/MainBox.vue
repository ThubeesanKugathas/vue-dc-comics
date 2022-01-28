<template>
    <main>
        <div class="ms_container">
            <div class="ms_current-series">
                <h2>CURRENT SERIES</h2>
            </div>
            <div v-for="(card, index) in comicsList" :key="index"
                class="ms_comics-card">
                <div class="ms_card-image">
                    <img :src="card.thumb" :alt="card.series">
                </div>
                <p>{{card.series.toUpperCase()}}</p>
            </div>
        </div>

        <span>
            <a href="#/">
                LOAD MORE
            </a>
        </span>
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
        padding: 50px 0 30px;

        .ms_container {
            width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            position: relative;

            .ms_current-series {
                position: absolute;
                top: -70px;
                left: 0%;
                background-color: $blue-color;
                padding: 10px 15px;
            }

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

        span {
            padding: 10px 50px;
            background-color: $blue-color;
            display: table;
            margin: 0 auto;
            font-weight: bold;
            cursor: pointer;

            a {
                text-decoration: none;
                color: $white-color;
            }
        }
    }
</style>