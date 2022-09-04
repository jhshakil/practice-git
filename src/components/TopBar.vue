<template>
    <div class="main-top">
        <div class="left-top">
            <div class="left-top left-margin">
                <svg width="13" height="18" viewBox="0 0 13 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M2.47665 1.03254L3.37332 0.745878C4.21415 0.477545 5.11249 0.911712 5.47249 1.76004L6.18915 3.45005C6.50082 4.18588 6.32749 5.05171 5.76082 5.59004L4.18165 7.08838C4.27915 7.98505 4.58082 8.86755 5.08582 9.73588C5.56538 10.576 6.20863 11.3113 6.97749 11.8984L8.87415 11.265C9.59249 11.0259 10.3758 11.3017 10.8158 11.9492L11.8433 13.4575C12.3558 14.2109 12.2633 15.2492 11.6275 15.8875L10.9467 16.5717C10.2683 17.2525 9.29915 17.5 8.40332 17.22C6.28665 16.56 4.34249 14.6009 2.56749 11.3425C0.789987 8.07921 0.162487 5.30921 0.685821 3.03588C0.905821 2.07921 1.58665 1.31671 2.47665 1.03254Z" fill="white"/>
                </svg>
            <small>02588867203</small>
            </div>
            <div class="left-top left-margin">
                <svg width="18" height="16" viewBox="0 0 18 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M16.5262 4.03321L9.70703 0.664068C9.48697 0.556123 9.24511 0.5 9 0.5C8.75489 0.5 8.51303 0.556123 8.29297 0.664068L1.47383 4.03321C1.10664 4.21136 0.797078 4.48936 0.580625 4.83536C0.364171 5.18135 0.249585 5.58134 0.250001 5.98946V13.2008C0.250001 14.407 1.24297 15.3883 2.46367 15.3883H15.5363C16.757 15.3883 17.75 14.407 17.75 13.2008V5.98946C17.7504 5.58134 17.6358 5.18135 17.4194 4.83536C17.2029 4.48936 16.8934 4.21136 16.5262 4.03321ZM8.85859 1.78204C8.90261 1.76045 8.95098 1.74922 9 1.74922C9.04902 1.74922 9.09739 1.76045 9.14141 1.78204L15.7578 5.05L9.03906 8.37032C8.99505 8.39191 8.94668 8.40313 8.89766 8.40313C8.84864 8.40313 8.80026 8.39191 8.75625 8.37032L2.13867 5.10196L8.85859 1.78204Z" fill="white"/>
</svg>
            <small>support@tutoracademia.com</small>
            </div>
        </div>
        <div class="right-top">
            <div class="social-icon">
                <!-- <img src="../assets/icons/facebook-f.svg" alt="fb icon"> -->
            </div>
            <div class="social-icon">
                <!-- <img src="../assets/icons/youtube.svg" alt="youtube icon"> -->
            </div>
            <div class="social-icon">
                <!-- <img src="../assets/icons/search.svg" alt="search icon"> -->
            </div>

        </div>
    </div>
</template>

<script>
export default {
    name: 'TopBar',
}
</script>

<style>
    .main-top {
        display: flex;
        justify-content: space-between;
        padding: 16px 149px;
        background-color: #0086AE;
        color: white;
        font-size: 16px;
    }

    .left-top {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .left-margin {
        margin-right: 16px;
    }

    .icon-svg {
        width: 11.67px;
        height: 16.63px;
        margin-right: 4.51px;
        border: none;
    }

    .right-top {
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .social-icon {
        width: 30px;
        height: 30px;
        background-color: white;
        border-radius: 50%;
        margin-right: 10px;
    }
    .social-icon img {
        width: 9.02px;
        height: 19.57px;
        margin-top: 5.82px;
        margin-left: 10.11px;
    }
</style>