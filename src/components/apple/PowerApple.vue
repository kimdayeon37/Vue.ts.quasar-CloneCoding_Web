<template>
    <!-- Power -->
    <section class="power">
      <div class="inner">

        <div class="multiple-apps">
          <h1 class="bgtext">
            거침없는 일 처리 성능.
          </h1>
          <div class="figures">
            <figure>
              <img src="/src/assets/images/power_multiple_apps.png" alt="Keynote 마크업과 메시지가 함께 표시된 Split View" />
              <figcaption class="bgtext">동시에 여러 앱 사용 가능</figcaption>
            </figure>
          </div>
        </div>

        <div class="arcade feature">
          <div class="figures">
            <figure>
              <img src="/src/assets/images/power_arcade.png" alt="iPad에 Wonderbox 앱이 열려 있는 모습" />
              <figcaption class="bgtext">신나게 즐기는 새로운 APPLE ARCADE 게임</figcaption>
            </figure>
          </div>
          <div class="infos infos--center">
            <div class="info">
              <div class="icon icon--chip"></div>
              <p>
                A13 Bionic 칩이 메시지 전송, 인터넷 서핑, 여러 앱 동시에
                사용하기 등 모든 작업에 더욱 탁월한 반응성을 더해줍니다.
              </p>
            </div>
            <div class="info">
              <div class="icon icon--faster"></div>
              <p>
                최대 20% 빨라진 GPU로 뛰어난 그래픽 성능을 선사합니다.
                몰입감 넘치는 게임 등 더 많은 것을 즐기는 데 안성맞춤이죠.
              </p>
            </div>
          </div>
        </div>

        <div class="create feature">
          <div class="infos infos--end">
            <div class="info">
              <div class="icon icon--neural"></div>
              <p>더욱 강력해진 Neural Engine이 iPadOS 15의 라이브 텍스트와 같은 머신 러닝 기반 기능을 구현해줍니다.</p>
            </div>
            <div class="info">
              <div class="icon icon--apps"></div>
              <p>A13 Bionic 칩은 Adobe Fresco, Procreate와 같은 첨단 앱도 거뜬히 구동합니다.</p>
            </div>
            <div class="info">
              <div class="icon icon--battery"></div>
              <p>
                온종일 가는 배터리를 갖춘 iPad. 당신이 열공 모드일 때도,
                게임 삼매경에 빠져 있을 때도 늘 함께할 준비가 되어 있습니다.<sup><a href="#footnote1">1</a></sup>
              </p>
            </div>
          </div>
          <div class="figures">
            <figure>
              <img src="/src/assets/images/power_create.jpg" alt="Procreate에서 Apple Pencil로 그림이 그려져 있는 모습" />
              <figcaption class="bgtext">스케치하고, 그리고, 색칠하고</figcaption>
            </figure>
          </div>
        </div>

      </div>
    </section>
</template>

<style scoped>
/* Power */
.power {
  margin-top: 110px;
}
/* Power / Multiple Apps */
.power .multiple-apps h1 {
  width: 500px;
  height: 280px;
  background-image: url("/src/assets/images/power_headline.png");
  transform: translate(104px, 0);
}
.power .multiple-apps .figures {
  height: 773px;
}
.power .multiple-apps figcaption {
  width: 138px;
  height: 46px;
  background-image: url("/src/assets/images/power_multiple_apps_caption.png");
  transform: translate(703px, -47px);
}

/* Power / Arcade */
.power .arcade {
  margin-top: 55px;
}
.power .arcade .figures {
  height: 600px;
}
.power .arcade figure {
  transform: translate(-347px, -90px);
}
.power .arcade figcaption {
  width: 150px;
  height: 77px;
  background-image: url("/src/assets/images/power_arcade_caption.png");
  transform: translate(483px, 653px);
}

/* Power / Create */
.power .create {
  margin-top: 55px;
}
.power .create .figures {
  height: 772px;
}
.power .create figure {
  transform: translate(-25px, 50px);
}
.power .create figcaption {
  width: 142px;
  height: 46px;
  background-image: url("/src/assets/images/power_create_caption.png");
  transform: translate(543px, 908px);
}
</style>