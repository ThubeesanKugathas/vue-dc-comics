<template>
    <div class="ms_ft-bottom">
        <div class="ms_container">
            <div class="ms_left">
                <h1>SIGN-UP NOW!</h1>
            </div>

            <div class="ms_right">
                <ul>
                    <li>FOLLOW US</li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
                    </li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
                    </li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
                    </li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
                    </li>
                    <li>
                        <img src="../assets/footer-facebook.png" alt="footer-facebook">
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
    .ms_ft-bottom {
        height: 100px;
        background-color: #333;

        .ms_container {
            width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;

            ul {
                display: flex;
                justify-content: end;

                li {
                    margin: 0 10px;
                }
            }
        }
    }
</style>