<template>
  <div>
    <body data-bs-spy="scroll" data-bs-target="#navbar">
      <header class="header">
        <nav class="navbar navbar-expand-lg fixed-top" id="navbar">
          <div class="container-fluid">
            <button
              class="navbar-toggler"
              type="button"
              data-bs-toggle="collapse"
              data-bs-target="#navbarSupportedContent"
              aria-controls="navbarSupportedContent"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div
              class="collapse navbar-collapse justify-content-center"
              id="navbarSupportedContent"
            >
              <ul class="navbar-nav mb-2 mb-lg-0">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#header"
                    >عني</a
                  >
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#licence">الشهادات والمؤهلات</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#statistics">المهارات</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#gallery">أعمالي</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#testimonials">أراء العملاء</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#contact-info">تواصل معي</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
        <div class="header" id="hheader">
          <div class="container">
            <div class="overlay text-center">
              <div class="personel">
                <img
                  src="../assets/hprofile.png"
                  style="width: 140px; height: 140px; margin-top: 30px"
                />
              </div>
              <h1>
                حسين محمد الطناني<span> - مطور واجهات المستخدم Vue.js</span>
              </h1>
              <ul class="list-inline">
                <li class="list-inline-item">
                  <a href=""><img src="../assets/linkedin24.png" /></a>
                </li>
                <li class="list-inline-item">
                  <a href=""><img src="../assets/facebook24.png" /></a>
                </li>
                <li class="list-inline-item">
                  <a href=""><img src="../assets/twitter.png" /></a>
                </li>
                <li class="list-inline-item">
                  <a href=""><img src="../assets/github24.png" /></a>
                </li>
              </ul>
              <h2>
                مطور واجهة الامستخدم مقيم بغزة أعمل بتصميم وتطوير المواقع منذ
                سنتين
              </h2>
              <br />
              -------
              <p>
                هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء لصفحة ما
                سيلهي القارئ عن التركيز على الشكل الخارجي للنص او شكل لوضع
                الفقرات
              </p>
              <a href="files/cv.pdf" class="cv"
                ><img src="../assets/direct-download24.png" />تحميل السيرة
                الذاتية</a
              >
            </div>
          </div>
        </div>
      </header>
    </body>

    <main>
      <section class="licence" id="licence">
        <div class="container">
          <div class="licence-title text-center">
            <h2>
              <img src="../assets/graduation64-cap-variant.png" />
              الشهادات والمؤاهلات
            </h2>
          </div>
          <ul class="timeline">
            <li>
              <div class="timebox">
                <h4><span>سبتمر 2022</span>بكالوريس في تكنولوجيا المعلومات</h4>
                <p>
                  هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء لصفحة ما
                  سيلهي القارئ عن التركيز على الشكل الخارجي للنص او شكل لوضع
                  الفقرات
                </p>
              </div>
            </li>
            <li>
              <div class="timebox">
                <h4><span>سبتمر 2022</span> كورس لغة انقليزية دبلوم</h4>
                <p>
                  هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء لصفحة ما
                  سيلهي القارئ عن التركيز على الشكل الخارجي للنص او شكل لوضع
                  الفقرات
                </p>
              </div>
            </li>
            <li>
              <div class="timebox">
                <h4><span>سبتمر 2022</span> كورس full stack لمدة اربع شهور</h4>
                <p>
                  هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء لصفحة ما
                  سيلهي القارئ عن التركيز على الشكل الخارجي للنص او شكل لوضع
                  الفقرات
                </p>
              </div>
            </li>
            <li>
              <div class="timebox">
                <h4>
                  <span>سبتمر 2022</span> تدريب في شركة برمجه في شركة لمده ثلاثة
                  شهور
                </h4>
                <p>
                  هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء لصفحة ما
                  سيلهي القارئ عن التركيز على الشكل الخارجي للنص او شكل لوضع
                  الفقرات
                </p>
              </div>
            </li>
          </ul>
        </div>
      </section>
      <section class="statistics" id="statistics">
        <div class="overlay">
          <div class="container">
            <div class="row">
              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-1">
                        <div class="fill-1"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-1"></div>
                      </div>
                      <div class="inside-circle">85%</div>
                    </div>
                  </div>
                </div>
                <P>HTML</P>
              </div>

              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-2">
                        <div class="fill-2"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-2"></div>
                      </div>
                      <div class="inside-circle">95%</div>
                    </div>
                  </div>
                </div>
                <P>CSS</P>
              </div>

              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-3">
                        <div class="fill-3"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-3"></div>
                      </div>
                      <div class="inside-circle">75%</div>
                    </div>
                  </div>
                </div>
                <P>Bootstrap</P>
              </div>

              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-4">
                        <div class="fill-4"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-4"></div>
                      </div>
                      <div class="inside-circle">45%</div>
                    </div>
                  </div>
                </div>
                <P>JavaScript</P>
              </div>

              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-5">
                        <div class="fill-5"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-5"></div>
                      </div>
                      <div class="inside-circle">55%</div>
                    </div>
                  </div>
                </div>
                <P>PHP</P>
              </div>

              <div class="col-sm-4 col-md-2">
                <div class="all">
                  <div class="circle-wrap">
                    <div class="circle">
                      <div class="mask full-6">
                        <div class="fill-6"></div>
                      </div>
                      <div class="mask half">
                        <div class="fill-6"></div>
                      </div>
                      <div class="inside-circle">60%</div>
                    </div>
                  </div>
                </div>
                <P>MySql</P>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section class="gallery text-center" id="gallery">
        <div class="gallery-title">
          <h2>
            <img src="../assets/coding.png" />
            الأعمال السابقة
          </h2>
        </div>
        <div class="container">
          <div class="gallery-work">
            <input
              type="radio"
              name="radio-set-1"
              id="item-type-all"
              class="item-type-all d-none"
              checked="checked"
            />
            <label for="item-type-all" class="label-type-all">الكل</label>

            <input
              type="radio"
              name="radio-set-1"
              id="item-type-1"
              class="item-type-1 d-none"
            />
            <label for="item-type-1" class="label-type-1">تصميم</label>

            <input
              type="radio"
              name="radio-set-1"
              id="item-type-2"
              class="item-type-2 d-none"
            />
            <label for="item-type-2" class="label-type-2">برمجة مواقع</label>

            <input
              type="radio"
              name="radio-set-1"
              id="item-type-3"
              class="item-type-3 d-none"
            />
            <label for="item-type-3" class="label-type-3"
              >تصميم تطبيقات الموبايل</label
            >
            <div class="row items">
              <div class="col-sm-6 col-md-4 item item-type-1">
                <img src="../assets/1.jpg" style="width: 340px" />
              </div>
              <div class="col-sm-6 col-md-4 item item-type-3">
                <img src="../assets/2.jpg" style="width: 340px" />
              </div>
              <div class="col-sm-6 col-md-4 item item-type-2">
                <img src="../assets/3.jpg" style="width: 340px" />
              </div>
              <div class="col-sm-6 col-md-4 item item-type-2">
                <img src="../assets/4.jpg" style="width: 340px" />
              </div>
              <div class="col-sm-6 col-md-4 item item-type-1">
                <img src="../assets/5.jpg" style="width: 340px" />
              </div>
              <div class="col-sm-6 col-md-4 item item-type-3">
                <img src="../assets/6.jpg" style="width: 340px" />
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="contacts" id="contacts">
        <div class="overlay">
          <div class="container">
            <div class="testimonials" id="testimonials">
              <div class="testimonials-title text-center">
                <h3>آراء العملاء</h3>
              </div>
              <div class="slider">
                <div id="carousel" class="carousel slide" data-bs-ride="true">
                  <div class="carousel-indicators">
                    <button
                      type="button"
                      data-bs-target="#carousel"
                      data-bs-slide-to="0"
                      class="active"
                      aria-current="true"
                      aria-label="Slide 1"
                    ></button>
                    <button
                      type="button"
                      data-bs-target="#carousel"
                      data-bs-slide-to="1"
                      aria-label="Slide 2"
                    ></button>
                    <button
                      type="button"
                      data-bs-target="#carousel"
                      data-bs-slide-to="2"
                      aria-label="Slide 3"
                    ></button>
                    <button
                      type="button"
                      data-bs-target="#carousel"
                      data-bs-slide-to="3"
                      aria-label="Slide 3"
                    ></button>
                  </div>
                  <div class="carousel-inner">
                    <div class="carousel-item active">
                      <div class="carousel-caption">
                        <img
                          src="../assets/per1.jpg"
                          class="rounded-circle"
                          alt=""
                        />
                        <h4>احمد ادم <span> - مصمم ويب بشركة جوجل</span></h4>
                        <p>
                          هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء
                          لصفحة ما سيلهي القارئ عن التركيز على الشكل الخارجي
                          للنص او شكل لوضع الفقرات
                        </p>
                        <!-- <ul class="list-inline">
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                        </ul> -->
                      </div>
                    </div>
                    <div class="carousel-item">
                      <div class="carousel-caption">
                        <img
                          src="../assets/per2.jpg"
                          class="rounded-circle"
                          alt=""
                        />
                        <h4>
                          ساره يوسف
                          <span> - مصممه جرافيك ديزاين بشركة جوال</span>
                        </h4>
                        <p>
                          هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء
                          لصفحة ما سيلهي القارئ عن التركيز على الشكل الخارجي
                          للنص او شكل لوضع الفقرات
                        </p>
                        <!-- <ul class="list-inline">
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                        </ul> -->
                      </div>
                    </div>
                    <div class="carousel-item">
                      <div class="carousel-caption">
                        <img
                          src="../assets/per3.jpg"
                          class="rounded-circle"
                          alt=""
                        />
                        <h4>حاتم خالد <span> - مبرمج BackEnd </span></h4>
                        <p>
                          هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء
                          لصفحة ما سيلهي القارئ عن التركيز على الشكل الخارجي
                          للنص او شكل لوضع الفقرات
                        </p>
                        <!-- <ul class="list-inline">
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                        </ul> -->
                      </div>
                    </div>
                    <div class="carousel-item">
                      <div class="carousel-caption">
                        <img
                          src="../assets/per4.jpg"
                          class="rounded-circle"
                          alt=""
                        />
                        <h4>نهى جميل <span> - مصمم UI/UX </span></h4>
                        <p>
                          هناك حقيقة مثبتة منذ زمن طويل وهي ان المحتوى القروء
                          لصفحة ما سيلهي القارئ عن التركيز على الشكل الخارجي
                          للنص او شكل لوضع الفقرات
                        </p>
                        <!-- <ul class="list-inline">
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                          <li class="list-inline-item">
                            <a href="">
                              <img src="../assets/github24.png" />
                            </a>
                          </li>
                        </ul> -->
                      </div>
                    </div>
                  </div>
                  <button
                    class="carousel-control-prev"
                    type="button"
                    data-bs-target="#carousel"
                    data-bs-slide="prev"
                  >
                    <img src="../assets/left-arrow11.png" />
                  </button>
                  <button
                    class="carousel-control-next"
                    type="button"
                    data-bs-target="#carousel"
                    data-bs-slide="next"
                  >
                    <img
                      src="../assets/right-arrow2.png"
                      style="background-color: bule"
                    />
                  </button>
                </div>
              </div>
            </div>
            <div class="contact-info" id="contact-info">
              <div class="contact-title text-center">
                <h3>تواصل معي</h3>
              </div>
              <div class="row">
                <div class="col-md-8">
                  <form class="contact-form row">
                    <div class="col-sm-6">
                      <input
                        type="text"
                        class="form-control"
                        placeholder="الاسم"
                      />
                    </div>
                    <div class="col-sm-6">
                      <input
                        type="email"
                        class="form-control"
                        placeholder="البريد الألكتروني"
                      />
                    </div>
                    <div class="col-12">
                      <textarea
                        class="form-control"
                        rows="5"
                        placeholder="نص الرسالة او تفاصيل المشروع"
                      ></textarea>
                    </div>
                    <button type="submit" class="btn">إرسال</button>
                  </form>
                </div>
                <div class="col-md-4">
                  <ul class="contact-us list-unstyled">
                    <li>
                      <img src="../assets/phone-bule.png" />
                      012 3456 7825
                    </li>
                    <li>
                      <img src="../assets/email-blue.png" />
                      email@example
                    </li>
                  </ul>
                  <hr />
                  <ul class="social list-inline">
                    <li class="list-inline-item">
                      <a href="">
                        <img src="../assets/google.png" />
                      </a>
                    </li>
                    <li class="list-inline-item">
                      <a href="">
                        <img src="../assets/facebook.png" />
                      </a>
                    </li>
                    <li class="list-inline-item">
                      <a href="">
                        <img src="../assets/twitte1r.png" />
                      </a>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
            <div class="copyright">
              <p>جميع الحقوق محفوظة</p>
            </div>
          </div>
        </div>
      </section>
    </main>
  </div>
</template>

<script>
// $(window).scroll(function () {
//   if ($(this).scrollTop() >= 200) {
//     $("#navbar").addClass("noTransparent");
//   } else {
//     $("#navbar").removClass("noTransparent");
//   }
// });
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

// export default {
//   name: "HomeView",
//   components: {
//     HelloWorld,
//   },
// };
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cairo:wght@200;300;400;500;600;700&display=swap");
* {
  font-family: "Cairo", sans-serif;
}
nav {
  margin: 0px !important;
  padding: 0px !important;
}
header.header {
  background-image: url(../assets/background1.jpg);
  background-size: cover;
  background-position: center;
  min-height: 400px;
  width: 100% !important;
  /* margin-right: -120px !important; */
  margin-top: -30px;
}
nav.navbar .navbar-nav li a.nav-link {
  color: #fff;
  font-size: 16px;
  line-height: 60px;
  padding-left: 24px;
  padding-right: 24px;
  transform: all 0.8s ease;
  margin-left: 20px;
}
nav.navbar .navbar-nav li a.nav-link:hover,
nav.navbar .navbar-nav li a.nav-link.active {
  color: #0575e6;
  background-color: #fff;
}
div .header .overlay {
  background-color: rgba(5, 117, 230, 0.9);
  color: #fff;
  padding: 20px 80px -20px;
  transform: translateY(20%);
}
div .header .personel img {
  border: 5px solid #73ade7;
  margin-bottom: 20px;
  border-radius: 80px;
}
div .header .overlay h1 {
  font-size: 36px;
  line-height: 50px;
  margin-bottom: 20px;
  color: #f9f9f9;
}
div .header .overlay h1 span {
  font-size: 24px;
}
div .header .overlay ul {
  margin-bottom: 40px;
}
div .header .overlay ul li a {
  font-size: 24px;
  color: #021b79;
}
div .header .overlay h2 {
  font-size: 15px;
  line-height: 30px;
  font-weight: bold;
  margin-bottom: 15px;
}
div .header .overlay p {
  font-size: 15px;
  line-height: 30px;
  color: #89c4ff;
  margin-bottom: 40px;
}
div .header .overlay a.cv {
  font-size: 18px;
  line-height: 32px;
  color: #fff;
  text-decoration: none;
  margin-bottom: 40px;
}
section.licence {
  padding: 200px 0 80px;
  background-color: #f6fbff;
}
section.licence .licence-title {
  padding-bottom: 30px;
  position: relative;
}
section.licence .licence-title h2 {
  font-size: 30px;
  line-height: 50px;
  color: #196dd1;
}
section.licence .licence-title h2::after {
  content: "";
  width: 100px;
  height: 2px;
  background-color: #196dd1;
  position: absolute;
  bottom: 0;
  right: 50%;
  transform: translateX(50%);
}

section.licence ul.timeline {
  padding-right: 0;
  padding-top: 45px;
  list-style: none;
  position: relative;
}
section.licence ul.timeline::before {
  content: "";
  width: 2px;
  height: 75%;
  position: absolute;
  top: 0;
  right: 50%;
  background-color: #196dd1;
  transform: translateX(50%);
}

section.licence ul.timeline li .timebox {
  background-color: #fff;
  border: 2px solid #f4f4f5;
  padding: 20px 25px;
  width: 48%;
  position: relative;
}
section.licence ul.timeline li .timebox h4 {
  font-size: 18px;
  line-height: 30px;
  color: #555;
}
section.licence ul.timeline li .timebox h4 span {
  color: #fff;
  background-color: #0575e6;
  padding: 0 5px;
  margin-left: 25px;
}
section.licence ul.timeline li .timebox p {
  font-size: 15px;
  line-height: 22px;
  color: #b1b1b1;
}
section.licence ul.timeline li .timebox::after {
  content: "";
  width: 20px;
  height: 20px;
  background-color: #fff;
  position: absolute;
  border-left: 2px solid #f4f4f5;
  border-bottom: 2px solid #f4f4f5;
  top: 5%;
  left: -10px;
  transform: rotate(45deg);
}

section.licence ul.timeline li {
  position: relative;
  margin-bottom: -50px;
}
section.licence ul.timeline li::before {
  content: "";
  width: 10px;
  height: 10px;
  border-radius: 50%;
  background-color: #196dd1;
  position: absolute;
  top: 10%;
  right: 51.4%;
  transform: translateX(50%);
}
section.licence ul.timeline li:nth-child(even) {
  direction: ltr;
  text-align: left;
  padding-right: 60px;
}
section.licence ul.timeline li:nth-child(even) .timebox::after {
  border: 0;
  left: auto;
  right: -10px;
  border-right: 2px solid #f4f4f5;
  border-top: 2px solid #f4f4f5;
}
section.licence ul.timeline li:nth-child(even) .timebox h4 span {
  float: left;
  margin-left: 0;
  margin-right: 25px;
}

section.statistics {
  background-image: url(../assets/back2.jpg);
  background-position: center;
  background-size: cover;
  background-attachment: fixed;
}

section.statistics .overlay {
  background-color: rgba(5, 117, 230, 0.7);
  padding: 150px 0;
}
section.statistics .overlay p {
  font-size: 24px;
  line-height: 30px;
  color: #fff;
  margin-top: 30px;
  font-family: sans-serif;
}
.all {
  display: flex;
}
.circle-wrap {
  display: grid;
  grid-template-columns: repeat(1, 160px);
  grid-gap: 80px;
  margin-top: 100px;
  margin-left: 50px;
  width: 150px;
  height: 150px;
  background-color: #d9d7da;
  border-radius: 50%;
}
.circle-wrap .circle .mask,
.circle-wrap .circle .fill-1,
.circle-wrap .circle .fill-2,
.circle-wrap .circle .fill-3,
.circle-wrap .circle .fill-4,
.circle-wrap .circle .fill-5,
.circle-wrap .circle .fill-6 {
  width: 150px;
  height: 150px;
  position: absolute;
  border-radius: 50%;
}
.circle-wrap .circle .mask {
  clip: rect(0px, 150px, 150px, 75px);
  /* background-color: black; */
}

.mask .fill-1 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-1,
.circle .fill-1 {
  animation: fill-1 ease-in-out 3s;
  transform: rotate(155deg);
}
@keyframes fill-1 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(155deg);
  }
}

.mask .fill-2 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-2,
.circle .fill-2 {
  animation: fill-2 ease-in-out 3s;
  transform: rotate(175deg);
}
@keyframes fill-2 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(175deg);
  }
}

.mask .fill-3 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-3,
.circle .fill-3 {
  animation: fill-3 ease-in-out 3s;
  transform: rotate(135deg);
}
@keyframes fill-3 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(135deg);
  }
}

.mask .fill-4 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-4,
.circle .fill-4 {
  animation: fill-4 ease-in-out 3s;
  transform: rotate(85deg);
}
@keyframes fill-4 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(85deg);
  }
}

.mask .fill-5 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-5,
.circle .fill-5 {
  animation: fill-5 ease-in-out 3s;
  transform: rotate(93deg);
}
@keyframes fill-5 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(93deg);
  }
}

.mask .fill-6 {
  clip: rect(0px, 75px, 150px, 0px);
  background-color: #021b79;
}
.mask.full-6,
.circle .fill-6 {
  animation: fill-6 ease-in-out 3s;
  transform: rotate(100deg);
}
@keyframes fill-6 {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(100deg);
  }
}
.inside-circle {
  width: 125px;
  height: 125px;
  border-radius: 50%;
  background: #0575e6;
  /* background-color: rgba(5, 117, 230, 0.7); */
  line-height: 120px;
  position: absolute;
  margin-top: 13px;
  margin-right: 13px;
  z-index: 100;
  font-size: 2em;
  font-weight: 700;
  color: #fff;
  text-align: center;
}
section.gallery {
  padding: 75px 0 90px;
}
section.gallery .gallery-title {
  margin-bottom: 35px;
}

section.gallery .gallery-title h2 {
  font-size: 30px;
  line-height: 50px;
  color: #0575e6;
}
section.gallery .gallery-work label {
  font-size: 18px;
  line-height: 35px;
  color: #8f9899;
  padding: 10px 30px;
  background-color: #fff;
  border: 2px solid #e4eeee;
  cursor: pointer;
  margin: 0 7px 40px;
  transition: all 0.6s ease;
}
section.gallery .gallery-work label:hover {
  color: #fff;
  background-color: #0575e6;
  border: 2px solid #0575e6;
}
section.gallery .gallery-work .items .item {
  margin-bottom: 25px;
  transition: all 0.5s ease;
}
section.gallery .gallery-work input.item-type-1:checked ~ label.label-type-1,
section.gallery .gallery-work input.item-type-2:checked ~ label.label-type-2,
section.gallery .gallery-work input.item-type-3:checked ~ label.label-type-3,
section.gallery
  .gallery-work
  input.item-type-all:checked
  ~ label.label-type-all {
  color: #fff;
  background-color: #0575e6;
  border: 2px solid #0575e6;
}
section.gallery .gallery-work input.item-type-1:checked ~ .items .item-type-1,
section.gallery .gallery-work input.item-type-2:checked ~ .items .item-type-2,
section.gallery .gallery-work input.item-type-3:checked ~ .items .item-type-3 {
  transform: scale(1.08);
  opacity: 1;
}

section.gallery
  .gallery-work
  input.item-type-1:checked
  ~ .items
  .item:not(.item-type-1),
section.gallery
  .gallery-work
  input.item-type-2:checked
  ~ .items
  .item:not(.item-type-2),
section.gallery
  .gallery-work
  input.item-type-3:checked
  ~ .items
  .item:not(.item-type-3) {
  transform: scale(0.8);
  opacity: 0.5;
}

section.contacts {
  background-image: url(../assets/bg-3.jpg);
  background-position: center;
  background-size: cover;
}
section.contacts .overlay {
  background-color: rgba(0, 0, 0, 0.6);
  padding-top: 70px;
}
section.contacts .overlay .testimonials-title h3 {
  font-size: 30px;
  line-height: 50px;
  color: #fff;
  margin-bottom: 40px;
}
section.contacts .overlay .testimonials .slider {
  width: 65%;
  margin: 0 auto 80px;
}
section.contacts .overlay .testimonials .slider .carousel-item {
  min-height: 350px;
}

section.contacts
  .overlay
  .testimonials
  .slider
  .carousel-item
  .carousel-caption {
  background-color: #fff;
  width: 100%;
  padding: 80px 70px 35px;
  right: 0;
}
section.contacts
  .overlay
  .testimonials
  .slider
  .carousel-item
  .carousel-caption
  img {
  position: absolute;
  top: 60px;
  transform: translate(50%, -50%);
}
section.contacts .overlay .testimonials .slider .carousel-caption h4 {
  font-size: 18px;
  color: #555;
  margin-bottom: 15px;
  margin-top: 60px;
}
section.contacts .overlay .testimonials .slider .carousel-caption h4 span {
  font-size: 15px;
  color: #9c9c9c;
  top: -10px;
}

section.contacts .overlay .testimonials .slider .carousel-caption p {
  font-size: 15px;
  line-height: 22px;
  color: #b1b1b1;
  margin-bottom: 25px;
  /* margin-top: 60px; */
}

section.contacts .overlay .testimonials .slider .carousel-caption li a img {
  font-size: 24px;
  color: #b2d8fa;
  transition: all 0.5s ease;
}
section.contacts .overlay .testimonials .slider .carousel-caption li a:hover {
  color: #0575e6;
}

section.contacts .overlay .testimonials .slider .carousel .carousel-indicators {
  bottom: -5px;
}

section.contacts
  .overlay
  .testimonials
  .slider
  .carousel
  .carousel-indicators
  button {
  width: 15px;
  height: 15px;
  border: 1px solid #0575e6;
  background-color: #fff;
}
section.contacts
  .overlay
  .testimonials
  .slider
  .carousel
  .carousel-indicators
  button.active {
  background-color: #0575e6;
}

section.contacts .overlay .testimonials .carousel .carousel-control-next img,
section.contacts .overlay .testimonials .carousel .carousel-control-prev img {
  padding: 10px 20px;
  background-color: #0575e6;
  border-radius: 80%;
}

section.contacts .overlay .testimonials .carousel .carousel-control-next {
  transform: translateX(50%);
}

section.contacts .overlay .testimonials .carousel .carousel-control-prev {
  transform: translateX(-50%);
}

section.contacts .overlay .contact-info {
  background-color: #fff;
  padding: 50px;
}

section.contacts .overlay .contact-info .contact-title {
  font-size: 30px;
  color: #0575e6;
  line-height: 50px;
  margin-bottom: 35px;
}

section.contacts .overlay .contact-info .contact-form input,
section.contacts .overlay .contact-info .contact-form textarea {
  border: 2px solid #f1f1f1;
  border-radius: 3px;
  font-size: 18px;
  color: #c2c2c2;
  line-height: 35px;
  padding-right: 45px;
  text-align: right;
  margin-bottom: 15px;
}
section.contacts .overlay .contact-info .contact-form .col-sm-6 {
  position: relative;
}
section.contacts .overlay .contact-info .contact-form .col-sm-6::before {
  font-family: "Font Awesome 5 Free";
  position: absolute;
  top: 0;
  right: 0;
  font-size: 18px;
  line-height: 25px;
  color: #0575e6;
  font-weight: 900;
}
/* section.contacts .overlay .contact-info .contact-form .col-sm-6:first-child::before {
  
  content: "/f007";
} */

section.contacts .overlay .contact-info .contact-form button {
  font-size: 24px;
  color: #0575e6;
  line-height: 25px;
  background-color: #fff;
  border: 3px solid #0575e6;
  padding: 15px 70px;
  border-radius: 3px;
  max-width: 200px;
  margin-right: 15px;
  transition: all 0.5s ease;
}

section.contacts .overlay .contact-info .contact-form button:hover {
  color: #fff;
  background-color: #0575e6;
}

section.contacts .overlay .contact-info ul.contact-us li {
  font-family: sans-serif;
  font-size: 16px;
  line-height: 30px;
  color: #0575e6;
}
section.contacts .overlay .contact-info ul.social li {
  margin-right: 10px;
}
section.contacts .overlay .contact-info ul.social li a {
  background-color: #9bc8f5;
  color: #fff;
  width: 50px;
  height: 50px;
  line-height: 50px;
  text-align: center;
  display: block;
  border-radius: 50%;
  transition: all 0.4s ease;
}
section.contacts .overlay .contact-info ul.social li a:hover {
  background-color: #0575e6;
}
section.contacts .overlay .copyright p {
  font-size: 18px;
  color: #ececec;
  line-height: 77px;
  margin: 0;
  text-align: center;
}
</style>
