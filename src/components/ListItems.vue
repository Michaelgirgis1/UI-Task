<template>
  <div class="container">
    <div class="games-list">
      <div class="row">
        <div class="col-2">
          <div class="games-list__categories">
            <div class="categories__item mb-10">
              <img
                src="./../assets/categories/used-active.png"
                alt="category image"
              />
            </div>
            <div class="categories__item mb-10">
              <img src="./../assets/categories/live.png" alt="category image" />
            </div>
            <div class="categories__item mb-10">
              <img
                src="./../assets/categories/sport.png"
                alt="category image"
              />
            </div>
            <div class="categories__item mb-10">
              <img
                src="./../assets/categories/lottery.png"
                alt="category image"
              />
            </div>
            <div class="categories__item mb-10">
              <img
                src="./../assets/categories/poker.png"
                alt="category image"
              />
            </div>
            <div class="categories__item">
              <img src="./../assets/categories/game.png" alt="category image" />
            </div>
          </div>
        </div>
        <div class="col-10">
          <div class="games-list__item mb-15">
            <img src="./../assets/games/game-1.png" alt="game image" srcset="" />
          </div>
          <div class="games-list__item mb-15">
            <img src="./../assets/games/game-2.png" alt="game image" srcset="" />
          </div>
          <div class="games-list__item mb-15">
            <img src="./../assets/games/game-3.png" alt="game image" srcset="" />
          </div>
          <div class="games-list__item">
            <img src="./../assets/games/game-4.png" alt="game image" srcset="" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style lang="scss">
.games-list {

    img {
        max-width: 100%;
    }
  }

</style>