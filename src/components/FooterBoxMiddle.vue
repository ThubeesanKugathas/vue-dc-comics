<template>
    <div class="ms_ft-middle">
        <div class="ms_container">
            <div class="ms_left">
                <ul class="ms_list">
                    <div class="ms_first-columns">
                        <li>
                            <p>DC COMICS</p>
                            <ul>
                                <li>Character</li>
                                <li>Character</li>
                                <li>Character</li>
                                <li>Character</li>
                                <li>Character</li>
                                <li>Character</li>
                                <li>Character</li>
                            </ul>
                        </li>

                        <li>
                            <p>DC COMICS</p>
                            <ul>
                                <li>Character</li>
                                <li>Character</li>
                            </ul>
                        </li>
                    </div>

                    <li>
                        <p>DC COMICS</p>
                        <ul>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                        </ul>
                    </li>

                    <li>
                        <p>DC COMICS</p>
                        <ul>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                            <li>Character</li>
                        </ul>
                    </li>
                </ul>
            </div>
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
        color: #fff;

        .ms_container {
            width: 1200px;
            margin: 0 auto;
            display: flex;

            .ms_list {
                display: flex;
                max-height: 100%;
            }
            img {
                height: 400px;
            }
        }
    }
</style>