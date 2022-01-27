<template>
    <nav>
        <div class="ms_left">
            <img src="@/assets/dc-logo.png" alt="dc-logo">
        </div>

        <div class="ms_right">
            <ul>
                <li>CHARACTERS</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>FANS</li>
            </ul>
        </div>
    </nav>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
    nav {
        width: 1200px;
        padding: 20px 0;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .ms_left {
            width: 40%;

            img {
                height: 80px;
            }
        }

        .ms_right {
            width: 60%;

            ul {
                display: flex;
                
                li {
                    margin: 0 10px;
                    font-size: 15px;
                    font-weight: bold;

                    &:hover {
                        border-bottom: 2px solid blue;
                    }
                }
            }
        }
    }
</style>