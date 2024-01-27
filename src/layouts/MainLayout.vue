<template>
  <q-layout view="lHh Lpr lFf">
    <q-header style="background-color: inherit; box-shadow: none; margin: 15px;">
      <q-toolbar>
        <q-toolbar-title style="margin-left: 25px;">
          BaraBank
        </q-toolbar-title>
        <q-space />
        <div class="q-gutter-sm">
          <q-btn flat label="صفحه اصلی" />
          <q-btn flat label="در باره ما" />
          <q-btn flat label="بلاگ" />
        </div>
        <q-space />

        <q-btn flat color="white" label="ورود و ثبت نام" to="/Signup"
          style="border: 2px solid  #24CDD8; border-radius: 64px; margin-right: 55px; padding: 13px 32px;" />
      </q-toolbar>
    </q-header>
    <div class="row" style="margin: 140px; ">
      <div class="col" style=" width: 640px;">
        <h1 class="text-h2" style="color: #ffff; direction: rtl;"><b>اولین کارت اعتباری ارز های دیجیتال</b> <br> </h1>
        <p style="color: #ADB2B1; direction: rtl;">به راحتی وارد بارا بانک شوید و کارت بانکی خودتون رو انتخاب کنید و در
          بحش ارزهای دیجیتال
          میتونید کارت اعتباری خودتون رو به کیف پول دیجیتال متصل کنید</p>
        <br>
        <div style="direction: rtl;">
          <q-btn label="شروع کنید"
            style="border: none; color: #fff; padding: 16px 32px; border-radius: 64px; background-color: #24CDD8;"></q-btn>
        </div>
      </div>
      <div class="col" style="604px">
        <img src="../assets/credit-card.svg" alt="Smartphone displaying MuseWallet app" />
      </div>
    </div>

    <div class="row about" style="width: 90%; margin: auto; text-align: center;">
      <div class="col">
        <h4>امنیت بالا</h4>
      </div>
      <div class="col">
        <h4>وام بدون ضامن</h4>
      </div>
      <div class="col">
        <h4>تراکنش نامحدود</h4>
      </div>
      <div class="col">
        <h4>هویت دیجیتالی</h4>
      </div>

    </div>

    <div class="row" style="margin: 140px; margin-top: 300px; ">
      <div class="col" style=" width: 640px;">
        <h1 class="text-h2" style="color: #ffff; direction: rtl;"><b>بارا بانک تجربه جدید بانک داری</b> <br> </h1>
        <p style="color: #ADB2B1; direction: rtl;">بارا بانک یک بانک غیر حضوری دیجیتال میباشد که علاوه بر انجام کارهای
          روزمره بانکی
          میتوانید پرداخت ها و تراکنش های ارزی خود را انجام دهید</p>
        <br>
        <div style="direction:  rtl;">
          <q-btn label="افتتحاح حساب"
            style="border: none; color: #fff; padding: 16px 32px; border-radius: 64px; background-color: #24CDD8;"></q-btn>
        </div>
      </div>
      <div class="col" style="604px">
        <img src="../assets/Group14.svg" alt="Smartphone displaying MuseWallet app" />

      </div>

    </div>

    <div class="row" style="margin: 140px; margin-top: 300px; ">

      <div class="col" style="604px">
        <img src="../assets/Group14(1).svg" alt="Smartphone displaying MuseWallet app" />

      </div>
      <div class="col" style=" width: 640px; padding-left: 30px;">
        <h1 class="text-h2" style="color: #ffff; direction: rtl;"><b>بهترین کارت اعتباری خودرا کشف کنید</b> <br> </h1>
        <p style="color: #ADB2B1; direction: rtl;">کارت اعتباری ایده آل خود را به راحتی کشف کنید. انتخاب جامع ما پاسخگوی
          هر نیاز مالی و
          سبک زندگی است. فرقی نمی‌کند به دنبال پاداش‌های برگشت نقدی، هدیه‌های سفر یا اعتبار ساخت هستید، ما کارت اعتباری
          عالی در انتظار شما هستیم. فرصت ها را آزاد کنید و کارت اعتباری متناسب با اهداف و آرزوهای منحصر به فرد خود را
          بیابید.</p>
        <br>
        <div style="direction: rtl;">
          <q-btn label="درخواست کارت جدید"
            style="border: none; color: #fff; padding: 16px 32px; border-radius: 64px; background-color: #24CDD8;"></q-btn>
        </div>
      </div>

    </div>















    <div class="accordion">
      <h1 style="color: white;">سوالات متداول</h1>
      <div class="accordion-item">
        <input type="checkbox" id="accordion1">
        <label for="accordion1" class="accordion-item-title"><span class="icon"></span>بارابانک چگونه کار میکند؟</label>
        <div class="accordion-item-desc">شما با افتتحاح حساب غیر حضوری دسترسی به تمام خدمات بانک داری خواهید داشت</div>
      </div>

      <div class="accordion-item">
        <input type="checkbox" id="accordion2">
        <label for="accordion2" class="accordion-item-title"><span class="icon"></span>بارابانک
          چگونه پرداخت های ارزی
          شمارا انجام میدهد ؟</label>
        <div class="accordion-item-desc">بارابانک یک صرافی غیر متمرکز میباشد که شما میتوانید دارایی های دیجیتال خود مانند
          بیت کوین و اتریوم و تتر و ... را به ریال تبدیل کرده و آنرا به صورت آنی خرج کنید</div>
      </div>

      <div class="accordion-item">
        <input type="checkbox" id="accordion3">
        <label for="accordion3" class="accordion-item-title"><span class="icon"></span>صرافی بارابانک چگونه کار
          میکند؟</label>
        <div class="accordion-item-desc">بعد از افتتحاح حساب به شما یک کیف پول دیجیتال با ادرس اختصاصی تعلق میگیرد و شما
          میتوانید دارایی های دیجیتال خود را در آن نگه داری کنید و با توجه به نرخ تبدیل ارز ها پول خود را تبدیل کنید</div>
      </div>

      <div class="accordion-item">
        <input type="checkbox" id="accordion4">
        <label for="accordion4" class="accordion-item-title"><span class="icon"></span>از کارت بارا در کجا ها میتوان
          استفاده کرد؟</label>
        <div class="accordion-item-desc">شما میتوانید در هر کجای دنیا کیف پول دیجیتال خود را با تتر شارژ کرده و با توجه به
          نوع ارز درگاه پرداخت تتر شما با نرخ تبدیل معلوم تبدیل به ارز درگاه پرداخت شده و پرداخت میشود</div>
      </div>

      <div class="accordion-item">
        <input type="checkbox" id="accordion5">
        <label for="accordion5" class="accordion-item-title"><span class="icon"></span>چگونه میتوان از بارابانک وام گرفت
          ؟</label>
        <div class="accordion-item-desc">شما با قرار دادن دارایی های دیجیتال خود به عنوان وثیقه میتوانید تا سقف صد میلیون
          تومان اعتبار دریافت کنید</div>
      </div>

    </div>

    <div class="row" style="margin: 140px; margin-top: 300px; ">
      <div class="col" style=" width: 640px; direction: rtl;">
        <h1 class="text-h2" style="color: #ffff; direction: rtl;"><b>به راحتی بارابانک را دریافت کنید</b> <br> </h1>
        <p style="color: #ADB2B1;">برنامه بارابانک را نصب کنید و وارد تجربه های جدید خود را شروع کنید</p>
        <br>
        <q-btn label="دانلود اپلیکشین"
          style="border: none; color: #fff; padding: 16px 32px; border-radius: 64px; background-color: #24CDD8;"></q-btn>
      </div>
      <div class="col" style="604px">
        <img src="../assets/image108.svg" alt="Smartphone displaying MuseWallet app" />

      </div>


    </div>


    <q-footer class="text-white"
      style="position: relative; background: rgba(40, 52, 48, 0.24); backdrop-filter: blur(8px);">
      <div class="row q-col-gutter-md">
        <div class="col-4 text-center" v-for="link in footerLinks" :key="link.title">
          <div class="text-h6 q-my-md">{{ link.title }}</div>
          <q-item v-for="name in link.names" :key="name" clickable>
            <q-item-section>{{ name }}</q-item-section>
          </q-item>
        </div>
      </div>
      <br>
      <div class="text-caption q-my-md text-center">

      </div>
    </q-footer>

  </q-layout>
</template>


<script>
export default {
  data() {
    return {
      footerLinks: [
        {
          title: 'درباره ما',
          names: ['سرمایه گزاران', 'دمو', 'امنیت']
        },
        {
          title: 'محصولات',
          names: ['کارت اعتباری', 'کارت هدیه', 'ان اف تی']
        },

        {
          title: 'بلاگ',
          names: ['تغییرات', 'اعتبار', 'مسیر', 'اخبار']
        }
        // Add more sections as needed
      ]
    }
  }
}
</script>


<style scoped>
.row.about {
  display: flexbox;
  padding: 25px;
  align-items: flex-start;
  border-radius: 32px;
  background: rgba(61, 84, 77, 0.24);
  backdrop-filter: blur(8px);
}

h3 {
  color: #FFF;
  font-family: M PLUS 1;
  font-size: 48px;
  font-style: normal;
  font-weight: 700;
  line-height: 56px;
  /* 116.667% */
  letter-spacing: -0.32px;
  align-items: center;
}

h4 {
  color: white;
}



.accordion {
  display: flex;
  flex-direction: column;
  font-family: "Sora", sans-serif;
  max-width: 991px;
  min-width: 320px;
  margin: 50px auto;
  padding: 0 50px;
}

.accordion h1 {
  font-size: 32px;
  text-align: center;
}

.accordion-item {
  margin-top: 16px;
  /* border: 1px solid #fcfcfc; */
  border-radius: 6px;
  /* background: #ffffff; */
  box-shadow: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  color: white;
}

.accordion-item .accordion-item-title {
  position: relative;
  margin: 0;
  display: flex;
  width: 100%;
  font-size: 15px;
  cursor: pointer;
  justify-content: space-between;
  flex-direction: row-reverse;
  padding: 14px 20px;
  box-sizing: border-box;
  align-items: center;
  direction: rtl;
}

.accordion-item .accordion-item-desc {
  display: none;
  font-size: 14px;
  line-height: 22px;
  font-weight: 300;
  color: #ffff;
  border-top: 1px solid #FFFF;
  padding: 10px 20px 20px;
  box-sizing: border-box;
  direction: rtl;
}

.accordion-item input[type="checkbox"] {
  position: absolute;
  height: 0;
  width: 0;
  opacity: 0;
}

.accordion-item input[type="checkbox"]:checked~.accordion-item-desc {
  display: block;
}

.accordion-item input[type="checkbox"]:checked~.accordion-item-title .icon:after {
  content: "-";
  font-size: 20px;
}

.accordion-item input[type="checkbox"]~.accordion-item-title .icon:after {
  content: "+";
  font-size: 20px;
}

.accordion-item:first-child {
  margin-top: 0;
}

.accordion-item .icon {
  margin-left: 14px;
}

@media screen and (max-width: 767px) {
  .accordion {
    padding: 0 16px;
  }

  .accordion h1 {
    font-size: 22px;
  }
}
</style>

