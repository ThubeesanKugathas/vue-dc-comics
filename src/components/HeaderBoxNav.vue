<template>
    <nav>
        <!-- logo left side del flex container -->
        <div class="ms_left">
            <img src="@/assets/dc-logo.png" alt="dc-logo">
        </div>

        <!-- bar right side del flex container -->
        <div class="ms_right">
            <ul>
                <li><a href="#">CHARACTERS</a></li>
                <li><a href="#">COMICS</a></li>
                <li><a href="#">MOVIES</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">GAMES</a></li>
                <li><a href="#">COLLECTIBLES</a></li>
                <li><a href="#">VIDEOS</a></li>
                <li><a href="#">FANS</a></li>
                <li><a href="#">NEWS</a></li>
                <li><a href="#">FANS</a></li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

    nav {
        width: $container-width;
        height: 100%;
        padding: 20px 0;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        // left side ---------------------------------
        .ms_left {
            width: 40%;

            img {
                height: 80px;
            }
        }

        // righ side --------------------------------
        .ms_right {
            width: 60%;

            ul {
                display: flex;
                
                li {
                    margin: 0 10px;
                    font-size: 15px;
                    font-weight: bold;

                    a {
                        text-decoration: none;
                        color: $grey-color;

                        &:hover {
                            border-bottom: 5px solid $blue-color;
                            color: $blue-color;
                        }
                    }
                }
            }
        }
    }
</style>