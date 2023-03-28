<template>
    <div class="container">
        <div class="back">
            <button>
                ←
            </button>
        </div>
        <div class="battle">
            <div class="left-battle-block">
                <div class="swipe-up">
                    <button>
                        ↑
                    </button>
                </div>
                <div class="data-car">
                    <div class="brand">
                        <p>
                            BMW
                        </p>
                    </div>
                    <div class="images">
                        <img src="../assets/x3.jpeg" alt="">
                    </div>
                    <div class="info">
                        <p>
                            Седан
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            3.0
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            98.000 км
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            Автомат
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            Серый
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            20 000 000 ₸
                        </p>
                    </div>
                </div>
                <div class="swipe-down">
                    <button>
                        ↓
                    </button>
                </div>
            </div>
            <div class="right-battle-block">
                <div class="swipe-up">
                    <button>
                        ↑
                    </button>
                </div>
                <div class="data-car">
                    <div class="brand">
                        <p>
                            BMW
                        </p>
                    </div>
                    <div class="images">
                        <img src="../assets/x6.jpeg" alt="">
                    </div>
                    <div class="info">
                        <p>
                            Кроссовер
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            3.5
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            120.000
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            Автомат
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            Красный
                        </p>
                    </div>
                    <div class="info">
                        <p>
                            28 500 000 ₸
                        </p>
                    </div>
                </div>
                <div class="swipe-down">
                    <button>
                        ↓
                    </button>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .container {
        display: grid;
        grid-template-columns: 0.13fr 1fr;
        max-width: 1180px;
        margin: 0 auto;
    }
    .back {
        margin-top: 40px;
    }
    .back button {
        font-size: 17px;
        padding: 0.3em 1.2em;
        border: transparent;
        box-shadow: 2px 2px 4px rgba(0,0,0,0.4);
        background: dodgerblue;
        color: white;
        border-radius: 4px;
    }

    .back button:hover {
        background: rgb(2,0,36);
        background: linear-gradient(90deg, rgba(30,144,255,1) 0%, rgba(0,212,255,1) 100%);
    }

    .back button:active {
        transform: translate(0em, 0.1em);
    }



    .battle {
        margin-top: 50px;
        gap: 100px;
        display: flex;
    }



    .swipe-up {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .swipe-up button {
        border: 1px solid #374151;
        border-radius: .75rem;
        box-sizing: border-box;
        color: #111827;
        cursor: pointer;
        font-family: "Inter var",ui-sans-serif,system-ui,-apple-system,system-ui,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
        font-size: 1.125rem;
        font-weight: 600;
        line-height: 1.5rem;
        padding: .6rem 1rem;
        text-align: center;
        }

    .swipe-up button:hover {
        color: #374151;
    }


    .swipe-down {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    .swipe-down button {
        border: 1px solid #374151;
        border-radius: .75rem;
        box-sizing: border-box;
        color: #111827;
        cursor: pointer;
        font-family: "Inter var",ui-sans-serif,system-ui,-apple-system,system-ui,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
        font-size: 1.125rem;
        font-weight: 600;
        line-height: 1.5rem;
        padding: .6rem 1rem;
        text-align: center;
        }

    .swipe-down button:hover {
        color: #374151;
    }
    .images img {
        width: 400px;
        height: 300px;
    }
    .brand {
        text-align: center;
    }
    .info {
        text-align: center;
    }
</style>

<script>
// export default {
//     methods: {
//         comparingData() {
//             const 
//         }
//     }
// }
</script>