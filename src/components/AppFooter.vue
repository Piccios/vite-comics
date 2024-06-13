<script>

</script>
<template>
    <footer>
        <section class="links">
            <section class="FooterContent">
                <div>
                    <ul>
                        <p>DC COMICS</p>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                        <li>link</li>
                    </ul>
                    <ul>
                        <p>SHOP</p>
                        <li>link</li>
                        <li>link</li>
                    </ul>
                </div>


                <ul>
                    <p>DC</p>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>
                <ul>
                    <p>SITES</p>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                    <li>link</li>
                </ul>

            </section>
            <section class="logo">
                <img src="../assets/img/dc-logo-bg.png" alt="dc_logo">
            </section>
        </section>
        <section class="social">
            <div class="signUp">
                <button>SIGN-UP NOW!</button>
            </div>
            <div class="socialLinks">
                <a href="">FOLLOW US</a>
                <img src="../assets/img/footer-facebook.png" alt="facebook_logo">
                <img src="../assets/img/footer-twitter.png" alt="Twitter_logo">
                <img src="../assets/img/footer-youtube.png" alt="Youtube_logo">
                <img src="../assets/img/footer-pinterest.png" alt="Pinterest_logo">
                <img src="../assets/img/footer-periscope.png" alt="Periscope_logo">
            </div>
        </section>
    </footer>

</template>
<style scoped>
section.links {
    height: 480px;
    background-image: url(../assets/img/footer-bg.jpg);
    display: flex;
    justify-content: space-around;
}

section.FooterContent {
    padding: 2rem;
    max-width: 80%;
    align-items: center;
}

ul p {
    font-size: 1.3rem;
    color: white;
    font-weight: 500;
}

ul li {
    color: grey;
    font-size: .8rem;
}

section.social {
    background-color: rgb(28, 28, 28);
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 130px;
    position: relative;
    z-index: 1;
}

div.socialLinks{
    text-align: center;
    align-items: center;
}

section.logo img{
    position: relative;
    bottom: 50px;
    z-index: 0;
    }
</style>