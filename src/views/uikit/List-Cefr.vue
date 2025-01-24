<script setup>

</script>

<template>
    <div class="grid">
        <div class="col-12">
            <div class="card test-text-wrapper" style="padding-bottom: 0.5rem !important;">
                <h5>CEFR<span class="blue-color text-left text-right">(Multilevel)</span>CERTIFICATES: <span class="blue-color">B1</span></h5>
                    <div class="col-12 p-0">
                        <div class="flex justify-content-space-evenly align-items-center w-full img-wrapper">
                            <Image src="/public/demo/images/certificates/cefr/3-attempt.jpg" class="with-image2" preview data-aos="fade-down"/>
                            <div class="with-image2 cefr-text-wrapper">
                                <h2 class="text">Listening: <span class="blue-color text-right">47</span></h2>
                                <h2 class="text">Reading: <span class="blue-color text-right">44</span></h2>
                                <h2 class="text">Writing: <span class="blue-color text-right">47</span></h2>
                                <h2 class="text">Speaking: <span class="blue-color text-right">45</span></h2>
                                <h2 class="text">Overall: <span class="blue-color text-right">46 (B1)</span></h2>
                            </div>
                        </div>
                    </div>
                    <div class="flex justify-content-evenly text-warpper">
                        <h5 class="text"><span class="blue-color">1st</span> ATTEMPT - TOTAL SCORE:<span class="blue-color text-right">46 (B1)</span></h5>
                    </div>
            </div>
        </div>
    </div>
</template>
<style lang="scss">
    .with-image2 {
        width: 31%;
        border-radius: 12px;
        cursor: pointer;
    }
    .img-wrapper > span > img {
        width: 100%;
        border: 1px solid var(--surface-border);
        box-shadow: var(--card-shadow);
        cursor: pointer;
    }
    .justify-content-space-between {
        justify-content: space-between !important;
    }
    .justify-content-space-evenly {
        justify-content: space-evenly !important;
    }
    .text {
        padding: 0 !important;
        margin: 25px 0 12px 0 !important;
    }
    .layout-content-wrapper {
        padding-bottom: 1rem !important;
    }
    .blue-color {
    color: #6366f1;
    }
    .p-image-preview-indicator {
        height: 99% !important;
    }
    .text-left {
        margin-right: 5px;
    }
    .text-right {
        margin-left: 5px;
    }
</style>