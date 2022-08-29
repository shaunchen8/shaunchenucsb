<template>
    <!-- <img src="@/assets/Shaun_Chen_Resume.jpg" alt="Resume" class="resume"> -->
    <div>&nbsp;</div>
    <div class="title">my engineering resume. updated june 2022</div>
    <iframe src="https://drive.google.com/file/d/1MdremrUpEX93bhOiGm4NXS3QsCke9b-n/preview" width="60%" ></iframe>

</template>

<style>
/* .resume{
    max-width: 100%;
    height: auto;
} */

/* small screen */
@media (max-width:1366px) {
    iframe {
        margin-top:100px;
    }
}

/* big screen */
@media (max-width:1920px) {
    iframe {
        height: 927px;
    }
}

.title{
    padding-top:5em;
    padding-bottom: 1em;
    font-family: Poppins;
    font-weight: bold;
    font-size: 24px;
}
</style>