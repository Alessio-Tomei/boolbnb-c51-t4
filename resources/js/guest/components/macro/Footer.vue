<template>
<footer>
    <div class="footer-container">
        <div class="footer-left">© 2022 BoolBnb, Inc.</div>
        <div class="footer-socials">
            <div><i class="fa-brands fa-facebook-f"></i></div>
            <div><i class="fa-brands fa-instagram"></i></div>
            <div><i class="fa-brands fa-twitter"></i></div>
        </div>
    </div>
</footer>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style lang="scss" scoped>
@import '../../../../sass/variables.scss';

footer{
    margin-top: 1rem;
    background: linear-gradient(0deg, rgba(144, 144, 144, 0.5) 0%, rgba(255,255,255,0) 60%);
    position: relative;
    bottom: 0;
    left: 0;
}
    .footer-container{
        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 3rem;
        width: calc(100% - 2rem);
        padding: 0 1rem;

        .footer-socials{
            display: flex;
            justify-content: space-evenly;
            align-items: center;
            & > *{
                font-size: 1.5rem;
                padding: 0 .3rem;
            }
        }
    }
</style>