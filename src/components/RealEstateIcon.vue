<script>
</script>

<template>
    <div class="realEstateIcon">
        <div class="realEstateIcon_picture">
            <div class="realEstateIcon_picture_1 picture">
                <img src="../../public/ICON1.png" alt="">
                <p class="realEstateIcon_picture_1_p1">不動産投資</p>
            </div>
            <div class="realEstateIcon_picture_2 picture">
                <img src="../../public/ICON2.png" alt="">
                <p class="realEstateIcon_picture_2_p2">不動産管理</p>
            </div>
            <div class="realEstateIcon_picture_3 picture">
                <img src="../../public/ICON3.png" alt="">
                <p class="realEstateIcon_picture_3_p3">売買及び賃貸</p>
            </div>
            <div class="realEstateIcon_picture_4 picture">
                <img src="../../public/ICON4.png" alt="">
                <p class="realEstateIcon_picture_4_p4">住宅ローン、保険等</p>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.realEstateIcon {
    .realEstateIcon_picture {
        margin-left: 20%;
        display: flex;

        .picture {
            img {
                width: 65%;
                height: 80%;
            }

            p {
                margin-left: 10%;
                color: #131840;
            }
        }

        .realEstateIcon_picture_4 {
            .realEstateIcon_picture_4_p4 {
                margin-left: -2%;
            }
        }
    }
}

@media screen and (min-width: 300px) and (max-width: 430px){
    .realEstateIcon {
    .realEstateIcon_picture {
        margin-left: 10%;
        display: flex;

        .picture {
            img {
                width: 50%;
                height: 80%;
            }

            p {
                margin-left: 5%;
                color: #131840;
                font-size: 0.5rem;
            }
        }

        .realEstateIcon_picture_4 {
            .realEstateIcon_picture_4_p4 {
                margin-left: -10%;
            }
        }
    }
}
}

@media screen and (min-width: 431px) and (max-width: 1024px) {
    .realEstateIcon {
        .realEstateIcon_picture {
            margin-left: 15%;

            .picture {
                p {
                    margin-left: 2%;
                }
            }

            .realEstateIcon_picture_4 {
                .realEstateIcon_picture_4_p4 {
                    margin-left: -12%;
                }
            }
        }
    }
}
</style>