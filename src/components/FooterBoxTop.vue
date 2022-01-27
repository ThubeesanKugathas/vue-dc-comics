<template>
    <div class="ms_ft-top">
        <ul>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="digital-comics">
                <p>DIGITAL COMICS</p>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    .ms_ft-top {
        background-color: #08f;
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
                    height: 70px;
                    margin-right: 10px;
                }
            }
        }
    }
</style>