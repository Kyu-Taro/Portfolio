<template>
  <div>
    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/sea.jpg')">
        <v-card-title class="title">写真共有投稿サービス</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>海の写真を題材に</div>

        <div>写真の投稿や回覧などが行える<br>フリー素材画像提供サービスです</div>
        <div>※使用技術　HTML CSS jQuery Laravel</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/sea-earth" text>GitHub</v-btn>

        <v-btn color="orange" href="http://seaearth.herokuapp.com/" text>Site</v-btn>
      </v-card-actions>
    </v-card>

    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/match.jpg')">
        <v-card-title class="title">エンジニアマッチングサービス</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>エンジニア専門のマッチングサービス</div>

        <div>共同開発するメンバーを募集し<br>マッチングを目的としたサービス</div>
        <div>※使用技術　HTML CSS jQuery Laravel</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/match-code_laravel" text>github</v-btn>

        <v-btn color="orange" href="https://www.match-code.site/" text>site</v-btn>
      </v-card-actions>
    </v-card>

    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/reserv.jpg')">
        <v-card-title class="title">飲食店予約システム</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>仮想飲食店のネット予約システム</div>
        <div>時間帯別で管理し予約できる制限をつけ</div>
        <div>予約できるよう設計しました</div>
        <div>※使用技術　HTML CSS PHP</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/Reservation" text>github</v-btn>
      </v-card-actions>
    </v-card>

    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/board.jpg')">
        <v-card-title class="title">掲示板サイト</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>投稿掲示板サイト</div>
        <div>管理者としての機能も実装</div>
        <div>※使用技術　HTML CSS jQuery Laravel</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/hikaru" text>github</v-btn>
      </v-card-actions>
    </v-card>

    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/ufarm.jpg')">
        <v-card-title class="title">野菜売買サービス</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>農家さんが野菜を出費しそれを直接購入することができる</div>
        <div>野菜を産地直送で購入できるサービス</div>
        <div>※現在開発中</div>
        <div>※使用技術　Nuxt(SPA) Laravel</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/u-farm"  text>Github</v-btn>
      </v-card-actions>
    </v-card>

    <v-card class="mx-auto" max-width="400">
      <v-img class="white--text align-end" height="200px" :src="require('~/assets/images/boards.jpg')">
        <v-card-title class="title">呟き掲示板</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>自由に呟くことのできる掲示板サイト</div>
        <div>ユーザー登録から投稿、削除、編集、プロフィール変更、退会などの機能を実装</div>
        <div>プロキシを利用し通信を行い<br>jwt atuh moduleを使用して認証しています</div>
        <div>※使用技術　HTML CSS Nuxt(SSR) Vuetify Laravel</div>
      </v-card-text>

      <v-card-actions>
        <v-btn color="orange" href="https://github.com/Kyu-Taro/u-farm"  text>Github</v-btn>
      </v-card-actions>
    </v-card>

  </div>
</template>

<style>
  .mx-auto {
    margin: 20px 0;
  }
  .title {
    background: rgba(0, 0, 0, 0.432);
  }
</style>
