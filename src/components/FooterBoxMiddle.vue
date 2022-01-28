<template>
    <div class="ms_ft-middle">
        <div class="ms_container">

            <!-- left side flex container -->
            <div class="ms_left">
                <ul class="ms_list">
                    <div class="ms_first-columns">
                        <li>
                            <p>DC COMICS</p>
                            <ul>
                                <li><a href="#/">Character</a></li>
                                <li><a href="#/">Comics</a></li>
                                <li><a href="#/">Movie</a></li>
                                <li><a href="#/">TV</a></li>
                                <li><a href="#/">Games</a></li>
                                <li><a href="#/">Videos</a></li>
                                <li><a href="#/">News</a></li>
                            </ul>
                        </li>

                        <li>
                            <p>SHOP</p>
                            <ul>
                                <li><a href="#/">Shop DC</a></li>
                                <li><a href="#/">Shop DC Collectibles</a></li>
                            </ul>
                        </li>
                    </div>

                    <li>
                        <p>DC</p>
                        <ul>
                            <li><a href="#/">Terms of use</a></li>
                            <li><a href="#/">Privacy policy (New)</a></li>
                            <li><a href="#/">Ad Choices</a></li>
                            <li><a href="#/">Advertising</a></li>
                            <li><a href="#/">Jobs</a></li>
                            <li><a href="#/">Subscriptions</a></li>
                            <li><a href="#/">Talent Workshop</a></li>
                            <li><a href="#/">CPSC Certificates</a></li>
                            <li><a href="#/">Ratings</a></li>
                            <li><a href="#/">Shop Help</a></li>
                            <li><a href="#/">Contact Us</a></li>
                        </ul>
                    </li>

                    <li>
                        <p>SITES</p>
                        <ul>
                            <li><a href="#/">DC</a></li>
                            <li><a href="#/">MAD Magazine</a></li>
                            <li><a href="#/">DC Kids</a></li>
                            <li><a href="#/">DC Universe</a></li>
                            <li><a href="#/">DC Power Visa</a></li>
                        </ul>
                    </li>
                </ul>
            </div>

            <!-- right side flex container -->
            <img src="../assets/dc-logo-bg.png" alt="dc-logo-bg">
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

    .ms_ft-middle {
        height: 400px;
        background: url(../assets/footer-bg.jpg) no-repeat;
        background-size: cover;

        .ms_container {
            width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;

            // left side -------------------------------
            .ms_list {
                display: flex;

                li {
                    margin-right: 20px;
                }

                p {
                    color: $white-color;
                    font-size: 20px;
                    font-weight: bold;
                    margin: 10px 0;
                }

                a {
                    text-decoration: none;
                    color: #888;
                }
            }

            // right side ------------------------------
            img {
                height: 400px;
            }
        }
    }
</style>