<template>
    <div class="ms_ft-top">
        <ul>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-merchandise.png" alt="merchandise">
                <p>MERCHANDISE</p>
            </li>
            <li>
                <img src="../assets/buy-comics-shop-locator.png" alt="shop-locator">
                <p>SHOP LOCATOR</p>
            </li>
            <li>
                <img src="../assets/buy-comics-subscriptions.png" alt="subscriptions">
                <p>SUBSCRIPTIONS</p>
            </li>
            <li>
                <img src="../assets/buy-dc-power-visa.svg" alt="dc-power-visa">
                <p>DC POWER VISA</p>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
// SCSS IMPORTS
@import '@/style/variables.scss';

    .ms_ft-top {
        background-color: $blue-color;
        height: 150px;

        ul {
            height: 100%;
            display: flex;
            justify-content: space-around;
            align-items: center;
            width: 1200px;
            margin: 0 auto;

            li {
                display: flex;
                align-items: center;

                img {
                    height: 60px;
                    margin-right: 10px;
                }

                p {
                    color: $white-color;

                    &:hover {
                        text-decoration: underline;
                        cursor: pointer;
                    }
                }
            }
        }
    }
</style>