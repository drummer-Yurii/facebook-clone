<script setup>
import { Head, usePage, Link } from '@inertiajs/vue3';
import MainNavLayout from '@/Layouts/MainNavLayout.vue';

import Magnify from 'vue-material-design-icons/Magnify.vue';
import TelevisionPlay from 'vue-material-design-icons/TelevisionPlay.vue';
import StorefrontOutline from 'vue-material-design-icons/StorefrontOutline.vue';
import AccountGroup from 'vue-material-design-icons/AccountGroup.vue';
import AccountMultiple from 'vue-material-design-icons/AccountMultiple.vue';
import Flag from 'vue-material-design-icons/Flag.vue';
import HomeOutline from 'vue-material-design-icons/HomeOutline.vue';
import ClockTimeTwoOutline from 'vue-material-design-icons/ClockTimeTwoOutline.vue';
import Restore from 'vue-material-design-icons/Restore.vue';
import VideoImage from 'vue-material-design-icons/VideoImage.vue';
import DotsHorizontal from 'vue-material-design-icons/DotsHorizontal.vue';

const user = usePage().props.auth.user
</script>

<template>
    <Head title="Posts" />

    <MainNavLayout>
       <div class="fixed w-full h-[100%] bg-[#F1F2F5]">
        <div class="grid grid-rows-3 grid-flow-col w-full max-w-[1600px] mt-[56px] h-[calc(100%-56px)] mx-auto px-4">

        </div>
       </div>
    </MainNavLayout>
</template>
