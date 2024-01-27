<template>
  <div class="signup">
    <div class="overlap-wrapper">
      <div class="overlap">
        <div class="overlap-group-2">
          <div class="ellipse"></div>
          <div class="ellipse-2"></div>
          <div class="frame-wrapper">
            <div class="frame-2">
              <div class="frame-3">
                <div class="upper-section">
                  <div class="login-text">
                    <div class="text-wrapper-2" style="position: relative; left: 142px;
  bottom: 20px;
;">ثبت نام</div>
                  </div>
                  <div class="credentials">
                    <input class="password" placeholder="نام کاربری" type="text" id="input-1" style="direction: rtl;" />

                    <input class="password" placeholder="شماره تلفن" type="text" style="direction: rtl;" id="input-1" />

                    <div class="password-rem">
                      <input class="password" placeholder="رمز عبور" type="password" id="input-1"
                        style="direction: rtl;" />
                      <input class="password" placeholder="تایید رمز عبور" type="password" id="input-1"
                        style="direction: rtl;" />
                    </div>
                    <div class="login-bt-fp" @click="showAlert">
                      <div class="login" style="cursor: pointer;">
                        <div class="text-wrapper-4" style="cursor: pointer;">ثبت نام </div>
                      </div>
                      <q-dialog v-model="alert" persistent>
                        <q-card>
                          <q-card-section>
                            ثبت نام شما با موفقیت انجام شد
                          </q-card-section>
                          <q-card-actions align="right">
                            <q-btn flat label="Close" v-close-popup />
                          </q-card-actions>
                        </q-card>
                      </q-dialog>
                    </div>
                  </div>
                </div>

              </div>

            </div>
          </div>
        </div>
        <img class="line-2" src="img/line-3.svg" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      alert: false
    }
  },
  methods: {
    showAlert() {
      this.alert = true
    }
  }
}
</script>



<style scoped>
.signup {
  background-color: #0e0e0e;
  display: flex;
  flex-direction: row;
  justify-content: center;
  width: 100%;
}

.signup .overlap-wrapper {
  background-color: #0e0e0e;
  overflow: hidden;
  width: 1440px;
  height: 1024px;
}

.signup .overlap {
  position: relative;
  width: 1387px;
  height: 936px;
  top: 60px;
  left: 60px;
}

.signup .overlap-group {
  position: absolute;
  width: 751px;
  height: 208px;
  top: 320px;
  left: 0;
}

.signup .text-wrapper {
  position: absolute;
  top: 0;
  left: 0;
  font-family: "Noto Sans-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .frame {
  display: inline-flex;
  align-items: flex-start;
  gap: 10px;
  padding: 14px 24px;
  position: absolute;
  top: 128px;
  left: 9px;
  border: 4px solid;
  border-color: #ffffff;
}

.signup .div {
  position: relative;
  width: fit-content;
  font-family: "Noto Sans-DisplaySemiBold Italic", Helvetica;
  font-weight: 600;
  font-style: italic;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .overlap-group-2 {
  position: absolute;
  width: 652px;
  height: 936px;
  top: 0;
  left: 735px;
}

.signup .ellipse {
  position: absolute;
  width: 302px;
  height: 302px;
  top: 0;
  left: 0;
  border-radius: 151px;
  background: linear-gradient(180deg, rgb(25.14, 0, 96.69) 0%, rgb(10.16, 27.48, 47.81) 100%);
}

.signup .ellipse-2 {
  position: absolute;
  width: 220px;
  height: 220px;
  top: 677px;
  left: 393px;
  border-radius: 110px;
  transform: rotate(-28.5deg);
  background: linear-gradient(180deg, rgb(0, 15.47, 96.69) 0%, rgb(10.16, 22.96, 47.81) 100%);
}

.signup .frame-wrapper {
  position: absolute;
  width: 482px;
  height: 798px;
  top: 53px;
  left: 104px;
  border-radius: 20px;
  overflow: hidden;
  border: 1px solid;
  border-color: transparent;
  box-shadow: -8px 4px 5px #0000003d;
  backdrop-filter: blur(53px) brightness(100%);
  -webkit-backdrop-filter: blur(53px) brightness(100%);
  border-image: linear-gradient(to bottom, rgb(255, 255, 255), rgba(0, 0, 0, 0)) 1;
  background: linear-gradient(180deg, rgba(191.25, 191.25, 191.25, 0.06) 0%, rgba(0, 0, 0, 0) 100%);
}

.signup .frame-2 {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  gap: 53px;
  position: relative;
  top: 97px;
  left: 40px;
}

.signup .frame-3 {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 16px;
  position: relative;
  flex: 0 0 auto;
}

.signup .upper-section {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 14px;
  position: relative;
  flex: 0 0 auto;
}

.signup .login-text {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  position: relative;
  flex: 0 0 auto;
}

.signup .text-wrapper-2 {
  font-size: 36px;
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  letter-spacing: 0;
  line-height: normal;
}

.signup .p {
  position: relative;
  width: fit-content;
  font-family: "Noto Sans-Medium", Helvetica;
  font-weight: 500;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .credentials {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 25px;
  position: relative;
  flex: 0 0 auto;
}

.signup .div-wrapper {
  display: flex;
  width: 400px;
  align-items: center;
  gap: 10px;
  padding: 14px 16px;
  position: relative;
  flex: 0 0 auto;
  border-radius: 12px;
  border: 1px solid;
  border-color: #ffffff;
}

.signup .text-wrapper-3 {
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .password-rem {
  display: inline-flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 12px;
  position: relative;
  flex: 0 0 auto;
}

.signup .password {
  width: 400px;
  padding: 14px 16px;
  position: relative;
  border-radius: 12px;
  border: 1px solid;
  border-color: #ffffff;
  background: none;
  margin-top: -1px;
  font-family: "Noto Sans-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 20px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .login-bt-fp {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 12px;
  position: relative;
  flex: 0 0 auto;
}

.signup .login {
  display: flex;
  width: 400px;
  align-items: center;
  justify-content: center;
  gap: 10px;
  padding: 14px 10px;
  border-radius: 12px;
  background: linear-gradient(91deg, #2E4CEE 9.91%, #221EBF 53.29%, #040F75 91.56%);


  position: relative;
  flex: 0 0 auto;
}

.signup .text-wrapper-4 {
  font-size: 20px;
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-SemiBold", Helvetica;
  font-weight: 600;
  color: #ffffff;
  letter-spacing: 0;
  line-height: normal;
}

.signup .other-logins {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  gap: 12px;
  position: relative;
  flex: 0 0 auto;
}

.signup .or {
  display: inline-flex;
  align-items: center;
  gap: 20px;
  position: relative;
  flex: 0 0 auto;
}

.signup .line {
  position: relative;
  width: 170px;
  height: 2px;
}

.signup .text-wrapper-5 {
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-Medium", Helvetica;
  font-weight: 500;
  color: #4c4c4c;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .img {
  position: relative;
  flex: 0 0 auto;
}

.signup .frame-4 {
  display: inline-flex;
  flex-direction: column;
  align-items: center;
  gap: 8px;
  position: relative;
  flex: 0 0 auto;
}

.signup .text-wrapper-6 {
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-Medium", Helvetica;
  font-weight: 500;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .customer-care {
  display: flex;
  width: 400px;
  align-items: center;
  justify-content: space-between;
  padding: 4px 6px;
  position: relative;
  flex: 0 0 auto;
  border-radius: 6px;
  background: linear-gradient(180deg, rgba(97.75, 97.75, 97.75, 0) 0%, rgba(97.75, 97.75, 97.75, 0.07) 100%);
}

.signup .frame-5 {
  display: inline-flex;
  align-items: flex-start;
  gap: 10px;
  position: relative;
  flex: 0 0 auto;
}

.signup .text-wrapper-7 {
  position: relative;
  width: fit-content;
  margin-top: -1px;
  font-family: "Noto Sans-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 16px;
  letter-spacing: 0;
  line-height: normal;
}

.signup .line-2 {
  position: absolute;
  width: 575px;
  height: 2px;
  top: 488px;
  left: 256px;
}
</style>
