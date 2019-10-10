<template>
    <div class="bgFxQW">
        <img src="https:////storage.googleapis.com/fe-production/images/banner-main-vi.jpg"
             alt="Đặt vé xe limousine của 1000+ hãng xe VIP đi toàn quốc"
             class="jUOtsM">
        <div class="kjFqFd">
            <div class="bGqzvX">
                <h1 class="hoUnZO">Góp phần cho hành trình của bạn hạnh phúc hơn</h1>
                <div class="dbtGmv">
                    <div>
                        <div class="jkwiLX">
                            <div class="ant-row-flex">
                                <div class="fIqoKh ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-lg-18">
                                    <div class="ant-row-flex">
                                        <div class="epOKdU ant-col-xs-24  ant-col-sm-24 ant-col-md-24 ant-col-lg-8 md-mb-8">
                                            <div class="jXJBhl">
                                                <div class="ghBeQA">
                                                    <div class="gZRXuM">
                                                        <svg class="faoMZh"
                                                             id="placeholder-filled-point"
                                                             xmlns="http://www.w3.org/2000/svg"
                                                             viewBox="0 0 11.781 16">
                                                            <!--                                                            <defs>-->
                                                            <!--                                                                <style>.svg-location{fill:#5090e9}</style>-->
                                                            <!--                                                            </defs>-->
                                                            <path class="svg-location"
                                                                  d="M18.773 0a5.9 5.9 0 0 0-5.89 5.891A5.746 5.746 0 0 0 13.4 8.3a37.14 37.14 0 0 0 5.127 7.591.328.328 0 0 0 .5 0A37.159 37.159 0 0 0 24.149 8.3a5.743 5.743 0 0 0 .515-2.4A5.9 5.9 0 0 0 18.773 0zm0 8.95a3.06 3.06 0 1 1 3.06-3.06 3.063 3.063 0 0 1-3.06 3.06z"
                                                                  transform="translate(-12.883)">
                                                            </path>
                                                        </svg>
                                                    </div>
                                                    <!--                                                    <input class="ant-input VXRSelect__input VXRSelect2__Input-tefulz-0 bMDsfW" placeholder="Nhập nơi đi" type="text" value="Hà Nội">-->
                                                    <v-select v-model="from" placeholder="Nhập nơi đi"
                                                              :options="options">
                                                        <span slot="no-options">Không tìm thấy</span>
                                                    </v-select>
                                                </div>
                                            </div>
                                            <div @click="swap" class="fYpVyH d-md-none">
                                                <svg class="jwDAek"
                                                     xmlns="http://www.w3.org/2000/svg"
                                                     width="28"
                                                     height="28"
                                                     viewBox="0 0 28 28">
                                                    <g stroke="#0060c4">
                                                        <g fill="#fff">
                                                            <circle cx="14" cy="14" r="14" stroke="none"></circle>
                                                            <circle cx="14" cy="14" r="13.5" fill="none"></circle>
                                                        </g>
                                                        <path fill="none" stroke-linecap="round" stroke-miterlimit="10"
                                                              d="M20 10.5H8.5M20.5 10.5L17 7M20.5 10.5L17 14M19.5 17.5H9M8 17.5l3.5-3.5M11.5 21L8 17.5">
                                                        </path>
                                                    </g>
                                                </svg>
                                            </div>
                                            <div class="jsdFhZ d-md-none"></div>
                                        </div>
                                        <div class="fAGyPa ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-lg-8 md-mb-8">
                                            <div class="kyXtnm">
                                                <div class="ghBeQA">
                                                    <div class="gZRXuM">
                                                        <svg class="faoMZh"
                                                             id="placeholder-filled-point"
                                                             xmlns="http://www.w3.org/2000/svg"
                                                             viewBox="0 0 11.781 16">
                                                            <!--                                                            <defs>-->
                                                            <!--                                                                <style>.svg-location{fill:#5090e9}</style>-->
                                                            <!--                                                            </defs>-->
                                                            <path class="svg-location"
                                                                  d="M18.773 0a5.9 5.9 0 0 0-5.89 5.891A5.746 5.746 0 0 0 13.4 8.3a37.14 37.14 0 0 0 5.127 7.591.328.328 0 0 0 .5 0A37.159 37.159 0 0 0 24.149 8.3a5.743 5.743 0 0 0 .515-2.4A5.9 5.9 0 0 0 18.773 0zm0 8.95a3.06 3.06 0 1 1 3.06-3.06 3.063 3.063 0 0 1-3.06 3.06z"
                                                                  transform="translate(-12.883)">
                                                            </path>
                                                        </svg>
                                                    </div>
                                                    <!--                                                    <input class="ant-input VXRSelect__input VXRSelect2__Input-tefulz-0 bMDsfW" placeholder="Nhập nơi đến" type="text" value="Hà Nội">-->
                                                    <v-select v-model="to" placeholder="Nhập nơi đến"
                                                              :options="options">
                                                        <span slot="no-options">Không tìm thấy</span>
                                                    </v-select>
                                                </div>
                                                <div class="jsdFhZ d-md-none"></div>
                                            </div>
                                        </div>
                                        <div class="krWMaZ ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-lg-8 md-mb-8">
                                            <div class="ftSWJG">
                                                <span class="dFcWyt ant-input-affix-wrapper ant-input-affix-wrapper-lg">
                                                    <span class="ant-input-prefix">
                                                        <svg class="eqZzUd"
                                                             xmlns="http://www.w3.org/2000/svg"
                                                             width="20.471"
                                                             height="22.745"
                                                             viewBox="0 0 20.471 22.745">
                                                            <g fill="#1861c5">
                                                                <path d="M18.196 2.275h-1.137V0h-2.274v2.275h-9.1V0H3.412v2.275H2.275A2.264 2.264 0 0 0 .012 4.55L.001 20.472a2.274 2.274 0 0 0 2.275 2.275h15.92a2.274 2.274 0 0 0 2.271-2.276V4.549a2.274 2.274 0 0 0-2.271-2.274zm0 18.2H2.275V7.961h15.921z"></path>
                                                                <path d="M13.394 18.954h3.033v-2.148h-3.033v2.148zM8.593 18.954h3.033v-2.148H8.593v2.148zM3.896 18.954h3.033v-2.148H3.896zM13.394 15.552h3.033v-2.148h-3.033v2.148zM8.593 15.659h3.033v-2.148H8.593v2.148zM6.824 13.511H3.791v2.148h3.033zM13.394 12.257h3.033v-2.148h-3.033v2.148zM8.593 12.257h3.033v-2.148H8.593v2.148zM3.896 12.257h3.033v-2.148H3.896z"></path>
                                                            </g>
                                                        </svg>
                                                    </span>
                                                    <datepicker v-model="date" placeholder="Nhập ngày đi"
                                                                :language="languages[language]"
                                                                format="dd-MM-yyyy"></datepicker>
                                                </span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="ksaiWq ant-col-xs-24 ant-col-sm-24 ant-col-md-24 ant-col-lg-6">
                                    <div class="encbDi">
                                        <button type="button" class="ant-btn eJOMls ant-btn-block">
                                            <span>Tìm vé xe</span>
                                        </button>
                                    </div>
                                </div>
                                <div @click="swap" class="fxmhwz d-lg-none">
                                    <svg class="gMJebn"
                                         xmlns="http://www.w3.org/2000/svg"
                                         viewBox="0 0 18 19.586">
                                        <path class="svg-exchange"
                                              d="M9.431 14.254l-.863.863 4.284 4.284a.612.612 0 0 0 .863 0L18 15.117l-.869-.863-3.238 3.244V0h-1.224v17.5zM5.324 19.586V2.088l3.233 3.243.869-.869L5.147.178a.612.612 0 0 0-.863 0L0 4.462l.863.863 3.238-3.238v17.5z"></path>
                                    </svg>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    import Datepicker from "vuejs-datepicker/dist/vuejs-datepicker.esm.js";
    import * as lang from "vuejs-datepicker/src/locale";

    export default {
        name: "HomePage",
        components: {
            Datepicker
        },
        data() {
            return {
                language: "vi",
                languages: lang,
                date: '',
                options: ['Hà Nội', 'Quảng Ninh', 'Hưng Yên'],
                from: '',
                to: ''
            };
        },
        methods: {
            swap() {
                const temp = this.to;
                this.to = this.from;
                this.from = temp;
            }
        },
        watch: {
            date() {
                console.log(this.date);
                return this.date;
            },
            from() {
                console.log(this.from);
                return this.from;
            },
            to() {
                console.log(this.to);
                return this.to;
            }
        }
    }
</script>

<style>
    /*@import "~vue-select/src/scss/vue-select.scss";*/
    /*@import '~vue-select/dist/vue-select.css';*/
    .v-select.vs--single.vs--searchable {
        background: #fff;
    }

    .vs__dropdown-toggle {
        -moz-appearance: none;
        appearance: none;
    }

    .vs__selected-options {
        display: flex;
        align-items: center;
    }


    .vs__dropdown-menu {
        display: block;
        position: absolute;
        top: calc(100% - 1px);
        left: 0;
        z-index: 1000;
        padding: 5px 0;
        margin: 0;
        width: 100%;
        max-height: 350px;
        min-width: 160px;
        overflow-y: auto;
        box-shadow: 0 3px 6px 0 rgba(0, 0, 0, .15);
        border: 1px solid rgba(60, 60, 60, .26);
        border-top-style: none;
        border-radius: 0 0 4px 4px;
        text-align: left;
        list-style: none;
        background: #fff;
    }

    .vs__search {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
        margin: 0;
        font-variant: tabular-nums;
        list-style: none;
        -webkit-font-feature-settings: 'tnum';
        font-feature-settings: 'tnum';
        position: relative;
        display: inline-block;
        /*width: 100%;*/
        height: 68px;
        padding: 4px 11px 4px 58px;
        color: rgba(0, 0, 0, 0.65);
        font-size: 20px;
        line-height: 1.5;
        background: none;
        /*border: 1px solid #d9d9d9;*/
        border-style: none;
        border-radius: 4px;
        -webkit-transition: all 0.3s;
        transition: all 0.3s;
        outline: none;
        appearance: none;
        -moz-appearance: none;
        box-shadow: none;
        width: 0;
        max-width: 100%;
        flex-grow: 1;
        flex-shrink: 0;
        flex-basis: 20%;
    }

    .vs__actions {
        display: none;
    }

    .vs__selected {
        display: flex;
        align-items: center;
        background-color: #f0f0f0;
        border: 1px solid rgba(60, 60, 60, .26);
        border-radius: 4px;
        color: #333;
        padding-left: 58px;
        font-size: 18px;
        /*background: transparent;*/
        flex-grow: 1;
        flex-shrink: 0;
        flex-basis: 80%;
    }

    .vs--single .vs__selected {
        background-color: transparent;
        border-color: transparent;
    }

    .vs--single.vs--open .vs__selected {
        position: absolute;
        opacity: .6;
    }

    .vs--single.vs--searching .vs__selected {
        display: none;
    }

    .vs__dropdown-menu {
        display: block;
        position: absolute;
        top: calc(100% - 1px);
        left: 0;
        z-index: 1000;
        padding: 5px 0;
        margin: 0;
        width: 100%;
        max-height: 350px;
        min-width: 160px;
        overflow-y: auto;
        box-shadow: 0 3px 6px 0 rgba(0, 0, 0, .15);
        border: 1px solid rgba(60, 60, 60, .26);
        border-top-style: none;
        border-radius: 0 0 4px 4px;
        text-align: left;
        list-style: none;
        background: #fff
    }

    .vs__dropdown-option {
        line-height: 1.42857143;
        display: block;
        padding: 3px 20px;
        clear: both;
        color: #333;
        white-space: nowrap
    }

    .vs__dropdown-option:hover {
        cursor: pointer
    }

    .vs__dropdown-option--highlight {
        background: #5897fb;
        color: #fff
    }

    .bgFxQW {
        width: 100%;
        height: calc(100vh - 60px);
        position: relative;
        display: flex;
        -webkit-box-align: center;
        align-items: center;
        -webkit-box-pack: center;
        justify-content: center;
        z-index: 1;
        transition: all 200ms ease 0s;
    }

    .jUOtsM {
        position: absolute;
        width: 100%;
        height: 100%;
        object-fit: cover;
        top: 0px;
        left: 0px;
        bottom: 0px;
        right: 0px;
    }

    img {
        vertical-align: middle;
        border-style: none;
    }

    .kjFqFd {
        position: relative;
        width: 980px;
        height: 100%;
        display: flex;
        -webkit-box-align: center;
        align-items: center;
        -webkit-box-pack: center;
        justify-content: center;
    }

    .bGqzvX {
        width: 100%;
    }

    .hoUnZO {
        font-size: 38px;
        font-weight: 500;
        margin-bottom: 22px;
        color: white;
        text-align: center;
    }

    .dbtGmv {
        width: 100%;
    }

    .jkwiLX {
        max-width: 1366px;
        position: relative;
        width: 100%;
        margin: auto;
        background: rgba(255, 255, 255, 0.64);
        border-radius: 5px;
    }

    .fIqoKh {
        position: relative;
    }

    .epOKdU {
        z-index: 3;
    }

    .jXJBhl {
        position: relative;
    }

    .ghBeQA {
        position: relative;
    }

    .gZRXuM {
        color: rgb(0, 122, 255);
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 24px;
        z-index: 2;
    }

    svg:not(:root) {
        overflow: hidden;
    }

    .faoMZh {
        width: 17px;
        height: 22px;
    }

    .epOKdU input {
        border-radius: 3px 0px 0px 3px;
    }

    .bMDsfW {
        height: 60px;
        width: 100%;
        padding-left: 58px;
        font-size: 20px;
        color: rgb(102, 102, 102);
        box-sizing: border-box;
        outline: none;
        border-width: initial;
        border-style: none;
        border-color: initial;
        border-image: initial;
    }

    .fAGyPa input {
        border-radius: 0px;
    }

    button, input {
        overflow: visible;
    }

    .fYpVyH {
        z-index: 4;
        right: 0px;
        top: 50%;
        transform: translate(50%, -50%);
        cursor: pointer;
        display: flex;
        -webkit-box-align: center;
        align-items: center;
        -webkit-box-pack: center;
        justify-content: center;
        position: absolute;
        background: white;
    }

    .jwDAek {
        width: 28px;
        height: 28px;
    }

    .jsdFhZ {
        width: 1px;
        height: 37px;
        position: absolute;
        right: 0px;
        top: 16px;
        background: rgb(187, 187, 187);
    }


    .fAGyPa {
        z-index: 2;
    }

    .kyXtnm {
        position: relative;
    }

    /*.kyXtnm > div > div {*/
    /*    left: 38px;*/
    /*}*/

    .kyXtnm .VXRSelect__input {
        padding-left: 72px;
    }

    .krWMaZ {
        z-index: 1;
    }

    .ftSWJG {
        position: relative;
    }

    .jkwiLX .ant-input-affix-wrapper .ant-input-prefix {
        left: 22px;
    }

    .dFcWyt input {
        height: 48px;
        outline: none;
        background: rgb(255, 255, 255);
        border-width: initial;
        border-style: none;
        border-color: initial;
        border-image: initial;
        border-radius: 0px;
    }

    .jkwiLX .ant-input-affix-wrapper input {
        border-color: rgb(228, 228, 228);
        border-radius: 0px;
    }

    .jkwiLX .ant-input-affix-wrapper > input:not(:first-child) {
        padding-left: 58px;
        font-size: 20px;
        color: rgb(102, 102, 102);
    }

    .ksaiWq {
        -webkit-box-flex: 1;
        flex-grow: 1;
    }

    .encbDi {
        text-align: center;
    }

    .eJOMls {
        height: 68px;
        color: rgb(72, 72, 72);
        text-transform: uppercase;
        font-weight: bold;
        font-size: 20px;
        border-width: initial;
        border-style: none;
        border-color: initial;
        border-image: initial;
        border-radius: 0px 3px 3px 0px;
        background: rgb(255, 197, 0);
    }

    .eJOMls:hover, .eJOMls:focus {
        background: rgb(255, 197, 0);
        color: rgb(72, 72, 72);
    }

    .faoMZh path {
        fill: rgb(24, 97, 197);
    }

    .fxmhwz {
        height: 44px;
        width: 44px;
        display: flex;
        -webkit-box-align: center;
        align-items: center;
        -webkit-box-pack: center;
        justify-content: center;
        position: absolute;
        right: 18px;
        top: 30px;
        border-radius: 22px;
        border-width: 1px;
        border-style: solid;
        border-color: rgb(228, 228, 228);
        border-image: initial;
        background: white;
        z-index: 10;
    }

    .gMJebn {
        width: 20px;
        height: auto;
    }

    .svg-exchange {
        fill: #5090e9;
    }

    .vdp-datepicker input {
        -webkit-box-sizing: border-box;
        box-sizing: border-box;
        margin: 0;
        font-variant: tabular-nums;
        list-style: none;
        -webkit-font-feature-settings: 'tnum';
        font-feature-settings: 'tnum';
        position: relative;
        display: inline-block;
        width: 100%;
        height: 48px;
        padding: 4px 11px 4px 58px;
        color: rgba(0, 0, 0, 0.65);
        font-size: 20px;
        line-height: 1.5;
        background-color: #fff;
        background-image: none;
        /*border: 1px solid #d9d9d9;*/
        border-radius: 4px;
        -webkit-transition: all 0.3s;
        transition: all 0.3s;
    }

    @media (min-width: 576px) {
        .eJOMls {
            height: 68px;
        }

        .dFcWyt input {
            height: 68px;
        }

        .jXJBhl .VXRSelect__input {
            height: 68px;
        }

        .kyXtnm .VXRSelect__input {
            height: 68px;
        }

        .vdp-datepicker input {
            height: 68px;
        }

    }

    @media (min-width: 992px) {
        .d-lg-none {
            display: none;
        }

        .ghBeQA .v-select {
            border-radius: 3px 0px 0px 3px;;
        }
    }

    @media (min-width: 1200px) {
        .epOKdU {
            margin: 0px;
        }

        .fAGyPa {
            margin: 0px;
        }

        .ksaiWq {
            margin: 0px;
        }

        .krWMaZ {
            margin: 0px;
        }

        .bGqzvX {
            margin-top: -50px;
        }

        .kyXtnm div div {
            left: 30px;
        }
        input.vs__search {
            padding-left: 60px;
        }
        .vs__selected {
            padding-left: 60px;
        }
    }


    @media (max-width: 991px) {
        .kyXtnm > div > div {
            left: 24px;
        }

        .kyXtnm .VXRSelect__input {
            padding-left: 58px;
        }

        .fYpVyH {
            right: 24px;
        }

        .hoUnZO {
            font-size: 24px;
            margin-bottom: 50px;
        }

        .md-mb-8 {
            margin-bottom: 8px;
        }

        .kjFqFd {
            padding: 94px 16px 28px;
            align-items: start;
        }

        .jkwiLX {
            background: unset;
        }

        .fIqoKh input {
            border-radius: 3px !important;
        }

        .d-md-none {
            display: none;
        }

        .jkwiLX .ant-input-affix-wrapper > input:not(:first-child) {
            font-size: 16px;
        }

        .bMDsfW {
            font-size: 16px;
        }

        .ksaiWq {
            margin-top: 8px;
        }

        .eJOMls {
            border-radius: 3px !important;
            font-size: 18px;
        }

        .fxmhwz {
            top: 50px;
        }

        .vdp-datepicker input {
            font-size: 16px;
            border-radius: 3px !important
        }

        .vs__selected {
            font-size: 16px;
        }

        .v-select {
            border-radius: 3px;
        }

        .vs__search {
            font-size: 16px;
        }
    }

    @media (max-width: 575px) {
        .jXJBhl .VXRSelect__input {
            height: 48px;
        }

        .kyXtnm .VXRSelect__input {
            height: 48px;
        }

        .eJOMls {
            height: 48px;
            font-size: 16px;
        }

        .fxmhwz {
            top: 32px;
            height: 36px;
            width: 36px;
        }

        .gMJebn {
            width: 16px;
        }

        .vs__search {
            height: 48px;
        }
    }

</style>
