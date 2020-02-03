<template>
  <div>
    <v-card class="mx-auto" max-width="400" color="#272727">
      <v-img class="white--text align-end" height="400px" :src="require('~/assets/images/profile.jpg')">
        <v-card-title class="title">Tsukasa Goto</v-card-title>
      </v-img>

      <v-card-text class="text--primary">
        <div>Name: Tsukasa Goto</div>
        <div>Birthday: 1995.9.30</div>
        <hr class="space">
        <div>
          エンジニア2年目、主にPHPやLaravelを独学にて2年学んでおりVue,Nuxtも並行して独学にて学んでいます。
          Nuxtを使った開発経験もあり、SPAでのサービス開発も行いました。また、Laravel×Nuxtでの開発を現在は行っています。
          普段からLaravelやNuxtの開発の練習等を独学にて行っており技術のキャッチアップなど積極的に行っています。
          現在までに使用or学んできた技術は、HTML CSS<br>
          JavaScript jQuery Vue.js Nuxt.js PHP Laravel SQL MySQL nginx apache Docker AWSになります。
        </div>
      </v-card-text>
    </v-card>

    <v-timeline :dense="$vuetify.breakpoint.smAndDown">
      <v-timeline-item
        color="purple lighten-2"
        fill-dot
        right
      >
        <v-card>
          <v-card-title class="purple lighten-2">
            <v-icon dark size="42" class="mr-4">
              mdi-chart-bubble
            </v-icon>
            <h2 class="display-1 white--text font-weight-light">2014年3月</h2>
          </v-card-title>
          <v-container>
            <v-row>
              <v-col cols="12" md="10">
                向陽台高等学校 普通科　卒業<br>
                通信制の高校だったため、飲食店へ就職し高校時代は飲食店で就業しており<br>
                接客をしていました。
              </v-col>
              <v-col
                class="hidden-sm-and-down text-right"
                md="2"
              >
                <v-icon size="64">mdi-calendar-text</v-icon>
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="amber lighten-1"
        fill-dot
        left
        small
      >
        <v-card>
          <v-card-title class="amber lighten-1 justify-end">
            <h2 class="display-1 mr-4 white--text font-weight-light">2014年4月</h2>
            <v-icon dark size="42" class="mr-4">
              mdi-chart-bubble
            </v-icon>
          </v-card-title>
          <v-container>
            <v-row>
              <v-col cols="12" md="8">
                岡和興産株式会社 入社<br>
                業務内容はパチンコ店での接客業務や事務業務<br>
                入社して3年目頃にIT業界に興味をもちプログラミングの独学を開始
                約4年間務めた会社を退職しエンジニアの道へいく
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="cyan lighten-1"
        fill-dot
        right
      >
        <v-card>
          <v-card-title class="cyan lighten-1">
            <v-icon dark size="42" class="mr-4">
              mdi-chart-bubble
            </v-icon>
            <h2 class="display-1 white--text font-weight-light">2018年12月</h2>
          </v-card-title>
          <v-container>
            <v-row>
              <v-col
                cols="12"
                md="42"
              >
              株式会社 イデアライブ　入社<br>
              エンジニアとしてのスタートとなった会社<br>
              在籍期間は約1年<br>
              業務としては、業務系システム開発がメインになり言語はC#を使っていました<br>
              今までの独学してきた内容とは全く違い戦力になれず、レポート作成やドキュメント作成など<br>
              コーディングより事務的な部分の作業が多く、これでは自身のエンジニアとしての技術を磨くのが難しいと思い転職を決意<br>
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="red lighten-1"
        fill-dot
        left
        small
      >
        <v-card>
          <v-card-title class="red lighten-1 justify-end">
            <h2 class="display-1 mr-4 white--text font-weight-light">2019年12月</h2>
            <v-icon dark size="42" class="mr-4">
              mdi-chart-bubble
            </v-icon>
          </v-card-title>
          <v-container>
            <v-row>
              <v-col cols="12" md="10">
                現職を退社し就職活動を開始<br>
                株式会社グロシードと出会い自分の求める技術を磨く環境があると確信し面接を申し込む<br>
                無事内定を頂き東京でのエンジニアとしてのスタートを切ることに成功する
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-timeline-item>

      <v-timeline-item
        color="green lighten-1"
        fill-dot
        right
      >
        <v-card>
          <v-card-title class="green lighten-1">
            <v-icon dark size="42" class="mr-4">
              mdi-chart-bubble
            </v-icon>
            <h2 class="display-1 white--text font-weight-light">2020年1月</h2>
          </v-card-title>
          <v-container>
            <v-row>
              <v-col>
                4月の入社までの期間、短期的にフリーランスとして活動することを決め契約を結ぶ<br>
                主にNuxtでの0からの開発案件にJOINすることが決まり<br>
                フロントエンジニアとして活動<br>
                フロントエンジニアは自分一人と言う状況でかつNuxtを理解しているメンバーは自分だけと言う環境<br>
                そんな中でいろんな課題にぶつかりながらも、Google先生の力を借りなんとか業務をこなす<br>
                現場での主な使用技術は、Nuxt,GCP, Docker, k8s, TypeScript, Express, CodeIgniter, GitHub Actions<br>
                と幅広い技術にふれました。<br>
                メインはNuxtでのフロント開発だっため、インフラ周りはあまり触れる機会はありませんでした。
              </v-col>
            </v-row>
          </v-container>
        </v-card>
      </v-timeline-item>
    </v-timeline>
  </div>
</template>

<style>
  .mx-auto{
    margin-top: 100px;
  }
  .space {
    margin: 10px 0;
  }
</style>
