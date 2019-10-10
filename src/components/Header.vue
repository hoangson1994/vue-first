<template>
    <div class="header_container cKqGNX">
        <div class="header-body">
            <div class="ant-row">
                <div class="ant-col ant-col-sm-24 ant-col-md-24 ant-col-lg-4 sm-m-auto">
                    <div class="logo">
                        <a href="#">
                            <img src="../assets/favicon-hoang-cong.png" alt="Logo">
                            <span>Hoang Cong</span>
                        </a>
                    </div>
                </div>
<!--                <div class="ant-col ant-col-md-20 d-none-xs">-->
<!--                    <ul>-->
<!--                        <li class="iMtEnK">-->
<!--                            <a href="#" class="frFZp">Xe Limousine</a>-->
<!--                        </li>-->
<!--                        <li class="iMtEnK">-->
<!--                            <a href="#" class="frFZp">Phần mềm nhà xe</a>-->
<!--                        </li>-->
<!--                        <li class="iMtEnK">-->
<!--                            <a href="#" class="frFZp">Quản lý vé</a>-->
<!--                        </li>-->
<!--                        <li class="Navbar__GroupItem-sc-19tf8g-3 iMtEnK">-->
<!--                            <a href="#" class="frFZp">EN<img src="https://storage.googleapis.com/fe-production/images/english_icon.png" alt="en" style="margin-bottom: 2px; margin-left: 4px;"></a>-->
<!--                        </li>-->
<!--                    </ul>-->
<!--                </div>-->
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Header"
    }
</script>

<style scoped>
    .logo a {
        height: 80px;
    }
    .logo a img {
        height: 44px;
        vertical-align: middle
    }
    .logo a span {
        height: 20px;
        position: relative;
        margin-left: 10px;
        color: #333333;
        font-weight: bold;
        font-size: 18px
    }
    .header {
        background: #333;
        color: #fff;
        text-align: center;
        padding: 10px;
    }
    .header a {
        color: #fff;
        padding-right: 5px;
        text-decoration: none;
    }
    .cKqGNX {
        display: flex;
        -webkit-box-align: center;
        align-items: center;
        min-height: 60px;
        box-shadow: rgba(0, 0, 0, 0.05) 0px 3px 5px;
    }
    .cKqGNX .header-body {
        width: 980px;
        margin: 0px auto;
    }
    .cKqGNX .header-body .ant-row {
        display: flex;
        -webkit-box-align: center;
        align-items: center;
    }

    .cKqGNX .header-body .ant-row ul {
        display: flex;
        -webkit-box-pack: end;
        justify-content: flex-end;
        margin-bottom: 0px;
        flex-wrap: wrap;
    }

    .cKqGNX .header-body .ant-row ul li {
        list-style-type: none;
        margin-left: 40px;
    }

    .iMtEnK {
        min-height: 60px;
    }

    .cKqGNX .header-body .ant-row ul li a {
        color: rgb(0, 0, 0);
    }

    .frFZp {
        font-size: 16px;
        line-height: 60px;
    }

    @media (max-width: 992px) {

        .logo {
            margin-left: 18px;
        }
    }

    @media (max-width: 767px) {

        .sm-m-auto {
            margin: auto;
        }

        .logo {
            margin-left: 0;
        }
    }

</style>
