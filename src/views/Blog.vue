<template>
    <div>
        <v-carousel class="pt-3">
            <v-carousel-item
            v-for="(item,i) in items"
            :key="i"
            :src="item.src"
            ></v-carousel-item>
        </v-carousel>
        <div class="divTopicImage pt-4 pb-4">
            <v-card-text class="fontIran text-xs-center">داستانی از دنیای بیت کوین و ارزهای دیجیتال</v-card-text>
        </div>
        <v-card-text class="pt-5">
            <span class="textFont" to="">ابزار بیشتر برای معاملات خاموش</span><br>
            <span class="textsFont">ما چندین ابزار را ایجاد کرده ایم که در موارد خاص می تواند معاملات با بیت کوین را ارزان تر کند. یکی از ویژگی های این نرم افزار تنها گزینه ی خاموش برای ابزار تجاری ما است. دیگر تگ recv در کد QR برای سپرده یا پرداخت صورتحساب است. توجه داشته باشید که این پست وبلاگ در راستای توسعه دهندگان، بازرگانان و / یا ارائه دهندگان خدمات است.</span><br>
            <router-link class="textCard" to="">ادامه مطلب</router-link><br>
            <div class="text-xs-left">
                <span class="">Jeremias</span><br>
                <span class="">September 28th, 2017</span><br>
            </div>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-text>
            <span class="textFont" to="">تغییرات ورود به صفحه سیستم</span><br>
            <span class="textsFont">ما قابلیت تصویر امنیتی را از صفحه ورود حذف کرده ایم.</span><br>
            <router-link class="textCard" to="">ادامه مطلب</router-link><br>
            <div class="text-xs-left">
                <span class="">Jeremias</span><br>
                <span class="">September 27th, 2017</span><br>
            </div>
        </v-card-text>
        
        <v-divider></v-divider>
        
        <v-card-text>
            <span class="textFont" to="">جبران برای کاربران متعلق به  تعادل BCH</span><br>
            <span class="textsFont">همانطور که بسیاری از شما آگاه هستند، یک رمزنگاری جدید به نام "Bcash" یا "Bitcoin cash" در تاریخ 1 آگوست 2017 ایجاد شد. این به طوری ایجاد شد که همه کسانی که دسترسی به یک کلید خصوصی داشتند، مبلغی معادل بیت کوین را دریافت می کردند از Bcash در بلاک چین دیگر. از آنجا که قطره هوا ما درخواست های زیادی برای ما برای شروع پشتیبانی از رمزنگاری جدید دریافت کرده ایم.</span><br>
            <router-link class="textCard" to="">ادامه مطلب</router-link><br>
            <div class="text-xs-left">
                <span class="">Max</span><br>
                <span class="">September 25th, 2017</span><br>
            </div>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-text>
            <span class="textFont" to="">بیانیه صدرکریپتو در مورد چنگال سخت ممکن در 1 آگوست 2017</span><br>
            <span class="textsFont">ما از لحاظ وضعیت فعلی با توجه به خطر افتادن بیتکوین در تاریخ 1 اوت، دقیقا تحت نظارت هستیم. امروز، 18 ژوئیه، احتمال دارد که چنگال سخت از زمانی که BIP 91 می تواند قبل از آن فعال شود، اجتناب شود.</span><br>
            <router-link class="textCard" to="">ادامه مطلب</router-link><br>
            <div class="text-xs-left">
                <span class="">Max</span><br>
                <span class="">July 19th, 2017</span><br>
            </div>
        </v-card-text>
        <v-divider></v-divider>
        <v-card-text class="pb-5">
            <span class="textFont" to="">سیستم جدید هزینه معامله بیت کوین</span><br>
            <span class="textsFont">صدرکریپتو یک سیستم هزینه جدید برای هزینه های شبکه بیت کوین استقرار دارد. ما هزینه بیت کوین را پایین می آوریم و هزینه های سپرده گذاری برای معاملات ورودی را معرفی می کنیم.</span><br>
            <router-link class="textCard" to="">ادامه مطلب</router-link><br>
            <div class="text-xs-left">
                <span class="">Jeremias</span><br>
                <span class="">June 13th, 2017</span><br>
            </div>
        </v-card-text>
        <Footer class="pt-5"></Footer>
    </div>
</template>
<script>
import Footer from './../components/Footer.vue'
  export default {
      components:{
          Footer,
      },
    data () {
      return {
        page: 1,
       items: [
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/squirrel.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/sky.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/bird.jpg'
          },
          {
            src: 'https://cdn.vuetifyjs.com/images/carousel/planet.jpg'
          }
        ]
      }
    }
  }
</script>
<style scoped>

.textFont{
    font-family:iranian sans;
    font-size:17px;
}
.textsFont{
    font-family:iranian sans;
    font-size:12px;
    color:#E0E0E0;
}
</style>
