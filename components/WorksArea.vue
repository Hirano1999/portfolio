<template>
  <div class="d-flex flex-column align-center">
    <H2>製作物</H2>

    <div class="d-flex flex-wrap justify-center">
      <v-card class="ma-2" max-width="300">
        <v-img src="/images/vrmanscg02deck.png" height="200px"></v-img>
        <v-card-title>VRMANSCG02 DECK</v-card-title>
        <v-card-text>
          VRカードゲーム『VRMANSCG02』のデッキ投稿サイトです。(注：カードゲームそのものは私の作品ではありません。)
        </v-card-text>
        <v-spacer />
        <v-card-actions>
          <v-btn
            target="_blank"
            color="primary"
            href="https://vrmanscg-decks-tel.netlify.app/"
            append-icon="mdi-open-in-new"
            >open</v-btn
          >
        </v-card-actions>
      </v-card>
      <v-card class="ma-2" max-width="300">
        <v-img src="/images/giantbattle.png" height="200px"></v-img>
        <v-card-title>ジャイアント・バトル</v-card-title>
        <v-card-text>
          自作VRカードゲーム『ジャイアントバトル』ワールドです。遊ぶにはVRCHATアカウントが必要です。
        </v-card-text>
        <v-card-actions>
          <v-btn
            target="_blank"
            color="primary"
            href="https://vrchat.com/home/world/wrld_84c94cf7-b0f1-4b34-9736-d8c5cefa040a"
            append-icon="mdi-open-in-new"
            >open</v-btn
          >
        </v-card-actions>
      </v-card>
    </div>
  </div>
</template>
