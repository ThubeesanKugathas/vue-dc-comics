<template>
    <div class="ms_ft-bottom">
        <div class="ms_container">
            <!-- left side flex container -->
            <div class="ms_left">
                <p>SIGN-UP NOW!</p>
            </div>

            <!-- right side flex container -->
            <div class="ms_right">
                <ul>
                    <li>FOLLOW US</li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
                    </li>
                    <li>
                        <img src="../assets/footer-twitter.png" alt="footer-twitter">
                    </li>
                    <li>
                        <img src="../assets/footer-youtube.png" alt="footer-youtube">
                    </li>
                    <li>
                        <img src="../assets/footer-pinterest.png" alt="footer-pinterest">
                    </li>
                    <li>
                        <img src="../assets/footer-periscope.png" alt="footer-periscope">
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '@/style/variables.scss';

    .ms_ft-bottom {
        height: 100px;
        background-color: $grey-color;

        .ms_container {
            width: 1200px;
            height: 100%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;

            // left side ----------------------------------------
            p {
                color: $white-color;
                border: 2px solid $blue-color;
                padding: 7px 10px;
                font-size: 20px;
            }
            
            // right side ---------------------------------------
            ul {
                display: flex;
                justify-content: end;
                align-items: center;

                li {
                    margin: 0 10px;

                    &:first-child {
                        color: $blue-color;
                        font-size: 20px;
                        font-weight: bold;
                    }
                }
            }
        }
    }
</style>