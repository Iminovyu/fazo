<template>
    <div class="nav">
        <div class="container">
            <div class="nav-content">
                <div class="nav-left">
                    <div class="nav-logo">
                        <img src="../assets/images/svg/logo.svg" alt="">
                    </div>
                    <div class="search">
                        <div class="search-input">
                            <button>
                                Все категории
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="##909090"
                                    xmlns="http://www.w3.org/2000/svg">
                                    <path d="M7 10L12 15" stroke="##909090" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                    <path d="M12 15L17 10" stroke="##909090" stroke-width="2" stroke-linecap="round"
                                        stroke-linejoin="round" />
                                </svg>
                            </button>
                            <div class="input">
                                <input type="text" placeholder="Телефоны и бытовая">
                                <span>
                                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <path
                                            d="M10 0.833008C9.33696 0.833008 8.70107 1.0964 8.23223 1.56524C7.76339 2.03408 7.5 2.66997 7.5 3.33301V9.99967C7.5 10.6627 7.76339 11.2986 8.23223 11.7674C8.70107 12.2363 9.33696 12.4997 10 12.4997C10.663 12.4997 11.2989 12.2363 11.7678 11.7674C12.2366 11.2986 12.5 10.6627 12.5 9.99967V3.33301C12.5 2.66997 12.2366 2.03408 11.7678 1.56524C11.2989 1.0964 10.663 0.833008 10 0.833008V0.833008Z"
                                            stroke="#BDBDBD" stroke-width="1.5" stroke-linecap="round"
                                            stroke-linejoin="round" />
                                        <path
                                            d="M15.8332 8.33301V9.99967C15.8332 11.5468 15.2186 13.0305 14.1246 14.1245C13.0307 15.2184 11.5469 15.833 9.99984 15.833C8.45274 15.833 6.96901 15.2184 5.87505 14.1245C4.78109 13.0305 4.1665 11.5468 4.1665 9.99967V8.33301"
                                            stroke="#BDBDBD" stroke-width="1.5" stroke-linecap="round"
                                            stroke-linejoin="round" />
                                        <path d="M10 15.833V19.1663" stroke="#BDBDBD" stroke-width="1.5"
                                            stroke-linecap="round" stroke-linejoin="round" />
                                        <path d="M6.6665 19.167H13.3332" stroke="#BDBDBD" stroke-width="1.5"
                                            stroke-linecap="round" stroke-linejoin="round" />
                                    </svg>
                                </span>
                            </div>
                        </div>
                        <button class="search-btn">
                            <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M9.16667 15.8333C12.8486 15.8333 15.8333 12.8486 15.8333 9.16667C15.8333 5.48477 12.8486 2.5 9.16667 2.5C5.48477 2.5 2.5 5.48477 2.5 9.16667C2.5 12.8486 5.48477 15.8333 9.16667 15.8333Z"
                                    stroke="white" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                <path d="M17.5 17.5L13.875 13.875" stroke="white" stroke-width="1.5" stroke-linecap="round"
                                    stroke-linejoin="round" />
                            </svg>
    
                            Поиск
                        </button>
                    </div>
                </div>
                <div class="nav-right">
                    <div class="item">
                        <div class="icon">
                            <svg width="20" height="22" viewBox="0 0 20 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M18.5716 20.6431V18.5003C18.5716 17.3636 18.12 16.2736 17.3163 15.4698C16.5126 14.6661 15.4225 14.2146 14.2859 14.2146H5.71443C4.57778 14.2146 3.48769 14.6661 2.68397 15.4698C1.88024 16.2736 1.42871 17.3636 1.42871 18.5003V20.6431M14.2859 5.64314C14.2859 8.01007 12.3671 9.92885 10.0001 9.92885C7.6332 9.92885 5.71443 8.01007 5.71443 5.64314C5.71443 3.2762 7.6332 1.35742 10.0001 1.35742C12.3671 1.35742 14.2859 3.2762 14.2859 5.64314Z"
                                    stroke="#202020" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" />
                            </svg>
    
                        </div>
                        <p>Войти</p>
                    </div>
                    <div class="item">
                        <div class="icon">
                            <svg xmlns="http://www.w3.org/2000/svg" height="24" width="30" viewBox="0 0 640 512">
                                <path
                                    d="M522.1 62.4c16.8-5.6 25.8-23.7 20.2-40.5S518.6-3.9 501.9 1.6l-113 37.7C375 15.8 349.3 0 320 0c-44.2 0-80 35.8-80 80c0 3 .2 5.9 .5 8.8L117.9 129.6c-16.8 5.6-25.8 23.7-20.2 40.5s23.7 25.8 40.5 20.2l135.5-45.2c4.5 3.2 9.3 5.9 14.4 8.2L288 480c0 17.7 14.3 32 32 32l192 0c17.7 0 32-14.3 32-32s-14.3-32-32-32l-160 0 0-294.7c21-9.2 37.2-27 44.2-49l125.9-42zM439.6 288L512 163.8 584.4 288l-144.9 0zM512 384c62.9 0 115.2-34 126-78.9c2.6-11-1-22.3-6.7-32.1L536.1 109.8c-5-8.6-14.2-13.8-24.1-13.8s-19.1 5.3-24.1 13.8L392.7 273.1c-5.7 9.8-9.3 21.1-6.7 32.1C396.8 350 449.1 384 512 384zM129.2 291.8L201.6 416 56.7 416l72.4-124.2zM3.2 433.1C14 478 66.3 512 129.2 512s115.2-34 126-78.9c2.6-11-1-22.3-6.7-32.1L153.2 237.8c-5-8.6-14.2-13.8-24.1-13.8s-19.1 5.3-24.1 13.8L9.9 401.1c-5.7 9.8-9.3 21.1-6.7 32.1z" />
                            </svg>
                        </div>
                        <p>Сравнение</p>
                    </div>
                    <div class="item">
                        <div class="icon">
                            <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M24.0619 7.06242C23.5383 6.52189 22.9166 6.0931 22.2324 5.80055C21.5481 5.508 20.8147 5.35742 20.0741 5.35742C19.3334 5.35742 18.6 5.508 17.9158 5.80055C17.2316 6.0931 16.6099 6.52189 16.0863 7.06242L14.9997 8.18369L13.913 7.06242C12.8554 5.97109 11.4209 5.35799 9.92522 5.35799C8.42952 5.35799 6.99507 5.97109 5.93744 7.06242C4.87981 8.15375 4.28564 9.63391 4.28564 11.1773C4.28564 12.7207 4.87981 14.2008 5.93744 15.2921L7.02408 16.4134L14.9997 24.6431L22.9752 16.4134L24.0619 15.2921C24.5857 14.7519 25.0013 14.1104 25.2848 13.4043C25.5683 12.6983 25.7142 11.9415 25.7142 11.1773C25.7142 10.413 25.5683 9.65627 25.2848 8.95022C25.0013 8.24418 24.5857 7.6027 24.0619 7.06242V7.06242Z"
                                    stroke="#202020" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" />
                            </svg>
                        </div>
                        <p>Избранное</p>
                    </div>
                    <div class="item">
                        <div class="icon">
                            <svg width="30" height="30" viewBox="0 0 30 30" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M2.14307 3.21387H6.42878L9.30021 17.5603C9.39819 18.0536 9.66654 18.4967 10.0583 18.812C10.45 19.1274 10.9402 19.2949 11.4431 19.2853H21.8574C22.3602 19.2949 22.8504 19.1274 23.2421 18.812C23.6339 18.4967 23.9022 18.0536 24.0002 17.5603L25.7145 8.57101H7.50021M11.7859 24.6424C11.7859 25.2342 11.3062 25.7139 10.7145 25.7139C10.1228 25.7139 9.64307 25.2342 9.64307 24.6424C9.64307 24.0507 10.1228 23.571 10.7145 23.571C11.3062 23.571 11.7859 24.0507 11.7859 24.6424ZM23.5716 24.6424C23.5716 25.2342 23.0919 25.7139 22.5002 25.7139C21.9085 25.7139 21.4288 25.2342 21.4288 24.6424C21.4288 24.0507 21.9085 23.571 22.5002 23.571C23.0919 23.571 23.5716 24.0507 23.5716 24.6424Z"
                                    stroke="#202020" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" />
                            </svg>
                        </div>
                        <p>Корзина</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="scss" scoped>
.nav {
    padding: 25px 0px;

    &-content {
        display: flex;
        align-items: center;
        justify-content: space-between;
    }

    &-left {
        display: flex;
        align-items: center;
        gap: 70px;

        .search {
            width: 720px;
            border: 1px solid #ED3729;
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-radius: 5px;

            .search-btn {
                padding: 16px 20px;
                color: #fff;
                font-family: "Nunito", sans-serif;
                font-size: 16px;
                font-weight: 600;
                line-height: 28.8px;
                border: 0;
                outline: 0;
                cursor: pointer;
                display: flex;
                align-items: center;
                gap: 15px;
                background: #ED3729;
            }

            &-input {
                padding: 13px;
                display: flex;
                align-items: center;
                width: 100%;

                .input {
                    width: 77%;
                    display: flex;
                    align-items: center;

                    input {
                        width: 80%;
                        border: 0;
                        outline: 0;
                    }

                    span {
                        margin-left: auto;
                    }
                }

                button {
                    background: transparent;
                    border: 0;
                    outline: 0;
                    cursor: pointer;
                    display: flex;
                    align-items: center;
                    gap: 5px;
                    width: 125px;
                    font-family: "Nunito", sans-serif;
                    font-size: 14px;
                    font-weight: 400;
                    line-height: 25.2px;
                }
            }
        }
    }

    &-right {
        display: flex;
        align-items: center;
        gap: 35px;

        .item {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
            justify-content: center;
        }
    }
}
</style>