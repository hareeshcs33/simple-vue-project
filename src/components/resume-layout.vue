<template>
<div>
    <div class="main-layout">
        <div class="left-side">
            <div class="img-box">
                <img src="../images/my-pic.png" width="200px" alt="My Image" />
            </div>
            <div class="nav-link-box">
                <ul class="navbar-nav">
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#about">About</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#experience">Experience</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#education">Education</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#skills">Skills</a></li>
                    <li class="nav-item"><a class="nav-link js-scroll-trigger" href="#interests">Interests</a></li>
                </ul>
            </div>
        </div>
        <div class="right-side">
            <!-- About-->
            <section class="resume-section" id="about">
                <div class="content-box">
                    <h1 class="profile-name">
                        HAREESH
                        <span> SAPPARAD</span>
                    </h1>
                    <h3 class="sub-title-name mb-3">#329-1, Nandagokula, 5th cross, Shanabag layout, Yamalur Bengaluru – 560037
                        Karnataka, India
                        <br/>
                        <div><a href="tel:+91 7259950413">+91 7259950413</a></div>
                        <span><a href="mailto:hareeshcs33@gmail.com">hareeshcs33@gmail.com</a></span>
                    </h3>
                    <p class="lead">Frontend developer with over 2 plus years of experience developing
                        Web Applications.
                    </p>
                    <p class="lead"></p>
                    <div class="social-icons">
                        <div class="social-icon" @click="redirectToLinkedIn"><svg class="svg-inline--fa fa-linkedin-in fa-w-14" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="linkedin-in" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" data-fa-i2svg=""><path fill="currentColor" d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z"></path></svg><!-- <i class="fab fa-linkedin-in"></i> --></div>
                        <div class="social-icon" @click="redirectToGithub"><svg class="svg-inline--fa fa-github fa-w-16" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" data-fa-i2svg=""><path fill="currentColor" d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg></div>
                        <div class="social-icon" @click="redirectToTwitter"><svg class="svg-inline--fa fa-twitter fa-w-16" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="twitter" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" data-fa-i2svg=""><path fill="currentColor" d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"></path></svg><!-- <i class="fab fa-twitter"></i> --></div>
                        <div class="social-icon" @click="redirectToFb"><svg class="svg-inline--fa fa-facebook-f fa-w-10" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="facebook-f" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512" data-fa-i2svg=""><path fill="currentColor" d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z"></path></svg><!-- <i class="fab fa-facebook-f"></i> --></div>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Experience-->
            <section class="resume-section" id="experience">
                <div class="content-box">
                    <h1 class="profile-exp mb-3">EXPERIENCE</h1>
                    <h2 class="mb-2">UI DEVELOPER</h2>
                    <h3 class="sub-title-name text-uppercase">V2 Solutions <small>(Mumbai)</small></h3>
                    <p><b>Clients:</b> Lending Tree <small>(USA)</small>.</p>
                    <p class="lead">Project Details – LendingTree is a Financial Web Application which gives
                         user a platform to reach out many Lenders for various loans purpose. 
                         User can compare the loans interest rates, Lender ratings/reviews. 
                         Can schedule a call with Lenders for further process.
                    </p>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Education-->
            <section class="resume-section" id="education">
                <div class="content-box">
                    <div class="resume-section-content">
                        <h1 class="mb-3">Education</h1>
                        <div class="d-flex flex-column flex-md-row justify-content-between mb-5">
                            <div class="flex-grow-1">
                                <h3 class="mb-0">AMC College of Engg. Bangalore</h3>
                                <div class="subheading mb-3">Mechanical Engineer</div>
                                <div>Interests In - Web Development Track</div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Skills-->
            <section class="resume-section" id="skills">
                <div class="content-box">
                    <div class="resume-section-content">
                        <h1 class="mb-3">Skills</h1>
                        <div class="subheading mb-3">Programming Languages & Tools</div>
                        <ul class="list-inline dev-icons">
                            <li class="list-inline-item"><i class="fab fa-html5"></i></li>
                            <li class="list-inline-item"><i class="fab fa-css3-alt"></i></li>
                            <li class="list-inline-item"><i class="fab fa-js-square"></i></li>
                            <li class="list-inline-item"><i class="fab fa-angular"></i></li>
                            <li class="list-inline-item"><i class="fab fa-vuejs"></i></li>
                            <li class="list-inline-item"><i class="fab fa-node-js"></i></li>
                            <li class="list-inline-item"><i class="fab fa-sass"></i></li>
                            <li class="list-inline-item"><i class="fab fa-less"></i></li>
                            <li class="list-inline-item"><i class="fab fa-npm"></i></li>
                        </ul>
                        <h3 class="subheading mb-3">Workflow</h3>
                        <ul class="fa-ul mb-0">
                            <li>
                                <span class="fa-li"><i class="fas fa-check"></i></span>
                                Mobile-First, Responsive Design
                            </li>
                            <li>
                                <span class="fa-li"><i class="fas fa-check"></i></span>
                                Cross Browser Testing & Debugging
                            </li>
                            <li>
                                <span class="fa-li"><i class="fas fa-check"></i></span>
                                Cross Functional Teams
                            </li>
                            <li>
                                <span class="fa-li"><i class="fas fa-check"></i></span>
                                Agile Development & Scrum
                            </li>
                        </ul>
                    </div>
                </div>
            </section>
            <hr class="m-0" />
            <!-- Interests-->
            <section class="resume-section" id="interests">
                <div class="content-box">
                    <div class="resume-section-content">
                        <h1 class="mb-3">Interests</h1>
                        <p>Apart from being a web developer, I enjoy most of my time being outdoors. 
                        <p class="mb-0">When forced indoors, I follow fantasy 
                            genre movies and television shows, I am an aspiring chef, and I spend a 
                            large amount of my free time exploring the latest technology advancements 
                            in the front-end web development world.</p>
                    </div>
                </div>
            </section>
        </div>
    </div>
</div>
</template>
<script>
export default {
    data(){
        return {
        }
    },
    methods: {
        redirectToLinkedIn(){
            console.log('clicked linkedIn link');
        },
        redirectToGithub(){
            console.log('clicked Github link');
        },
        redirectToTwitter(){
            console.log('clicked Twitter link');
        },
        redirectToFb(){
            console.log('clicked Fb link');
        },
    },
    components: {
    }
}
</script>
<style>
.main-layout {
    display: flex;
}
.left-side {
    background-image: linear-gradient(45deg, #ee9ca7 0%, #ffdde1 100%);
    width: 270px;
    height: 100vh;
    position: fixed;
}
.right-side {
    padding-left: 270px;
    width: 85%;
}
.img-box {
    width: 200px;
    height: 200px;
    overflow: hidden;
    margin: 30px auto;
    border-color: linear-gradient(#00cdac #8ddad5 100%);
    /* background-image: linear-gradient(-20deg, #00cdac 0%, #8ddad5 100%); */
    border-radius: 100%;
}
.img-box img {
    background-image: linear-gradient(-20deg, #ddd6f3 0%, #faaca8 100%, #faaca8 100%);
    border-radius: 100%;
    padding: 7px;
}
.nav-link-box .navbar-nav .nav-item a{
    text-align: center;
    font-weight: 600;
    letter-spacing: 0.05rem;
    text-transform: uppercase;
    background: -webkit-linear-gradient(#4fc8e8, #103b7d);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
.nav-link-box .navbar-nav .nav-item a:hover {
    background: -webkit-linear-gradient(#00c6fb, #005bea);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}
section {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
.content-box {
    width: 100%;
    padding: 30px;
}
.profile-name {
    color: #343a40;
    font-size: 90px;
    font-weight: 600;
    line-height: 1;
    margin: 0;
}
.profile-name span,
.sub-title-name span {
    color: #ee9ca7;
}
.sub-title-name {
    color: #6c757d;
    font-size: 24px;
    font-weight: 500;
}
.dev-icons {
    font-size: 48px;
}
.social-icons .social-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    height: 3.5rem;
    width: 3.5rem;
    background-color: #495057;
    color: #fff;
    border-radius: 100%;
    font-size: 1.5rem;
    margin-right: 1.5rem;
    cursor: pointer;
}
.social-icons .social-icon:hover {
    background-color: #ee9ca7;
}
</style>