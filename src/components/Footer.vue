<!--
 * @Author: your name
 * @Date: 2021-05-25 22:56:49
 * @LastEditTime: 2021-05-29 16:13:05
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: /oms-ux/Users/chenglei/work/WebStack-vue/src/components/Footer.vue
-->
<template>
    <footer class="main-footer sticky footer-type-1">
        <!-- <div class="bg-primary text-center">
            <div style="font-size: 20px">一起发现更多新产品</div>
            <a href="https://github.com/icpfans-xyz/123icp/issues" type="button"
                class="btn btn-warning btn-inline-block" style="margin-top: 20px;width: 100px;">提交</a>
        </div> -->
        <!-- <a href="https://github.com/icpfans-xyz/123icp/issues" type="button" class="btn btn-warning btn-lg btn-block">提交新产品</a> -->
        <div class="footer-inner">
            <!-- 版权信息 -->
            <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="120" height="20"
                role="img" aria-label="Dfinity ∞: deployed">
                <a xlink:href="https://rqmco-gyaaa-aaaad-qaclq-cai.raw.ic0.app/" target="_blank">
                    <title>Dfinity ∞: deployed</title>
                    <linearGradient id="s" x2="0" y2="100%">
                        <stop offset="0" stop-color="#bbb" stop-opacity=".1"></stop>
                        <stop offset="1" stop-opacity=".1"></stop>
                    </linearGradient>
                    <clipPath id="r">
                        <rect width="120" height="20" rx="3" fill="#fff"></rect>
                    </clipPath>
                    <g clip-path="url(#r)">
                        <rect width="61" height="20" fill="#555"></rect>
                        <rect x="61" width="59" height="20" fill="#007ec6"></rect>
                        <rect width="120" height="20" fill="url(#s)"></rect>
                    </g>
                    <g fill="#fff" text-anchor="middle" font-family="Verdana,Geneva,DejaVu Sans,sans-serif"
                        text-rendering="geometricPrecision" font-size="110">
                        <text aria-hidden="true" x="315" y="150" fill="#010101" fill-opacity=".3" transform="scale(.1)"
                            textLength="510">
                            Dfinity ∞</text>
                        <text x="315" y="140" transform="scale(.1)" fill="#fff" textLength="510">
                            Dfinity ∞</text><text aria-hidden="true" x="895" y="150" fill="#010101" fill-opacity=".3"
                            transform="scale(.1)" textLength="490">deployed</text>
                        <text x="895" y="140" transform="scale(.1)" fill="#fff" textLength="490">
                            deployed</text>
                    </g>
                </a>
            </svg>
            <div class="footer-text" style="margin-right: 15px;">
                &copy; 2021 Powered By 
                <a href="https://icpfans.xyz" target="_blank"><strong>ICPFans</strong></a>
                <!-- design by <a href="http://viggoz.com" target="_blank"><strong>Viggo</strong></a> -->
            </div>

            <div class="go-up">
                <a href="#" rel="go-top"><i class="fa-angle-up"></i></a>
            </div>
            <a href="https://github.com/icpfans-xyz/icp123/issues" type="button" target="_blank"
                class="btn btn-xs btn-warning btn-inline-block" style="float: right;margin-right: 15px; width: 100px;">提交更多作品</a>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style>
</style>
