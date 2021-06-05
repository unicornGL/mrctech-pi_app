<template lang="pug">
  .container
    .header
      img.logo(src="/logo.png")
      #companyName YouTube
      fa.searchIcon.fa-2x(:icon="fas.faSearch")
      .memberIcon: .memberAlpha S
    .filter
      .tag.all All
      .tag Music
      .tag One Piece
      .tag Anime
      .tag Love songs
      .tag G.E.M
      .tag WTO Sister Brew
      .tag Monster Hunter Rise
      .tag Front End
      .tag Back End
      .tag JavaScript
      .tag React.js
      .tag Next
      .tag Vue.js
      .tag Vuxt
      .tag This is a long tag
      .tag I have no idea what to write
    .content
      .video
        img.videoPic(src="/Joma Tech-Pic.png")
        .info
          img.channelLogo(src="/Joma Tech-Profile.png")
          .infoText
            .videoTitle chill lofi beats to code/relax to
            .infoDetail Joma Tech ‧ 572 watching ‧ 8 months ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/達康.come-Pic.png")
        .info
          img.channelLogo(src="/達康.come-Profile.png")
          .infoText
            .videoTitle 達康.come漫才《陳同學》
            .infoDetail 達康.come笑tube ‧ 746k views ‧ 2 years ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/Amanda-Pic.png")
        .info
          img.channelLogo(src="/Amanda-Profile.png")
          .infoText
            .videoTitle 蒋侍郎豆腐【曼达小馆】*4K
            .infoDetail 曼食慢语 Amanda Tastes ‧ 356k views ‧ 3 years ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/Amazing-Pic.png")
        .info
          img.channelLogo(src="/Amazing-Profile.png")
          .infoText
            .videoTitle 😱 Impossible Odds Challenge 😱 | That's Amazing
            .infoDetail That's Amazing ‧ 1.8M views ‧ 1 years ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/ufc-Pic.png")
        .info
          img.channelLogo(src="/ufc-Profile.png")
          .infoText
            .videoTitle UFC Debut: Conor McGregor vs Marcus Brimage | Free Fight
            .infoDetail UFC - Ultimate Fighting Championship ‧ 22M views ‧ 1 years ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/MCJeng-Pic.png")
        .info
          img.channelLogo(src="/MCJeng-Profile.png")
          .infoText
            .videoTitle 特別企劃，防疫外送餐點配酒開箱｜恩熙俊｜理性癮酒｜
            .infoDetail 恩熙俊 aka MC Jeng ‧ 67k views ‧ 7 hours ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/WG-Pic.png")
        .info
          img.channelLogo(src="/WG-Profile.png")
          .infoText
            .videoTitle 廚師長教你：“鹽焗海鮮”的家常做法，6斤“寬鹽”可以反複使用，鹽烤大蝦、海螺、鮑魚、蟶子！
            .infoDetail 美食作家王刚 ‧ 1.5M views ‧ 1 years ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
      .video
        img.videoPic(src="/木曜4超玩-Pic.png")
        .info
          img.channelLogo(src="/木曜4超玩-Profile.png")
          .infoText
            .videoTitle 《一日系列第一百五十七集》邰智源連拖吊車都會開了，違規車輛都給我注意一點!!－一日拖吊車作業人員
            .infoDetail 木曜4超玩 ‧ 784k views ‧ 2 days ago
          fa.ellipsisIcon.fa-lg(:icon="fas.faEllipsisV")
    .toolbar
      .tool
        fa.fa-2x(:icon="fas.faHome")
        .toolText Home
      .tool
        fa.fa-2x.other(:icon="fas.faFire")
        .toolText.other Trending
      .tool
        fa.fa-2x.other(:icon="fas.faThList")
        .toolText.other Subscriptions
      .tool
        fa.fa-2x.other(:icon="fas.faBook")
        .toolText.other Library
</template>

<script>
  import { fas } from '@fortawesome/free-solid-svg-icons'
  export default {
    computed: {
      fas () {
         return fas
      }
    }
  }
</script>

<style src="../assets/style.css">
  /* 一開始 init 沒設定到 Sass，所以我用 Sass Live Compiler 把 .scss 轉成 .css 再引入 */
</style>