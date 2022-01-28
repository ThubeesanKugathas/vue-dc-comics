<template>
    <main>
        <div class="ms_container">
            <!-- position absolute tag -->
            <div class="ms_current-series">
                <h2>CURRENT SERIES</h2>
            </div>

            <!-- v-for comics cards -->
            <div v-for="(card, index) in comicsList" :key="index"
                class="ms_comics-card">
                <div class="ms_card-image">
                    <img :src="card.thumb" :alt="card.series">
                </div>
                <p>{{card.series.toUpperCase()}}</p>
            </div>
        </div>

        <!-- load more button -->
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
// SCSS IMPORTS
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

            // position absolute tag ------------------------------------------
            .ms_current-series {
                position: absolute;
                top: -70px;
                left: 0%;
                background-color: $blue-color;
                padding: 10px 15px;
            }

            // comics cards ---------------------------------------------------
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

        // load more button ----------------------------------------------------------
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
            
            &:hover {
                text-decoration: underline;
            }
        }
    }
</style>