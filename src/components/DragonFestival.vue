<template>
  <div class="container">
    <section class="dragon-festival">
      <div class="row">
        <div class="col-5">
          <div class="dragon-festival__price">
            <div class="dragon-festival__price__img">
              <img
                src="./../assets/festival/price.png"
                alt="dragon festival price image "
                srcset=""
              />
            </div>
            <div class="dragon-festival__price__content">
              <div class="dragon-festival__price__content__crown">
                <img
                  class="ken-image"
                  src="./../assets/festival/KEN.png"
                  alt="ken image"
                  srcset=""
                />
                <img
                  class="crown-image"
                  src="./../assets/festival/crown.png"
                  alt="crown image"
                  srcset=""
                />
                <span>7</span>
              </div>

              <p><span>$</span>121212233</p>
            </div>
          </div>
        </div>
        <div class="col-2"></div>
        <div class="col-5">
          <div class="dragon-festival__brief">
            <p>
              <img
                src="./../assets/festival/price-voice.png"
                alt="dragon festival voice image "
                srcset=""
              />:Dragon Boat Festival holiday!holiday!holiday!holiday! Dragon
              Boat Festival
            </p>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style lang="scss">
@import "./../scss/_variables.scss";
.dragon-festival {
  margin-bottom: 15px;
  .row {
    width: 100%;
  }
  .dragon-festival__price {
    display: flex;
    align-items: flex-end;
    .dragon-festival__price__img {
      margin-inline-end: 15px;
      img {
        max-width: 30px;
      }
    }
  }
  .dragon-festival__price__content {
    .dragon-festival__price__content__crown {
      margin-bottom: 10px;
      display: flex;
      align-items: center;
      span {
        color: $primaryColor;
      }
    }
    img {
      margin-inline-end: 10px;
    }
    .crown-image {
      max-width: 24px;
    }
    .ken-image {
      max-width: 40px;
    }

    p {
      margin-bottom: 0;
      font-size: 20px;
      line-height: normal;
      span {
        color: #8b8780;
        font-size: 16px;
      }
    }
    > span,
    p {
      color: $primaryColor;
    }
  }
  .dragon-festival__brief {
    display: flex;
    align-items: self-start;
    img {
      margin-inline-end: 7px;
    }
    p {
      text-align: left;
      margin-bottom: 0;
      color: #8b8780;
      font-size: 14px;
    }
  }
}
</style>