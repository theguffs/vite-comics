<template>
  <main>
    <div class="content">
      <div class="comic-list">
        <div
          v-for="(comic, index) in comics"
          :key="index"
          class="comic-item"
        >
          <img :src="comic.thumb" :alt="comic.series" class="comic-thumb" />
          <h2>{{ comic.series }}</h2>
          <p>Price: {{ comic.price }}</p>
          <p>Type: {{ comic.type }}</p>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  data() {
    return {
      comics: [
        {
          thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb: "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb: "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb: "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb: "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg/revision/latest?cb=20080809201655",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg/revision/latest/scale-to-width-down/1200?cb=20130627211607",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg/revision/latest?cb=20200929145132",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg/revision/latest?cb=20200929124651",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg/revision/latest?cb=20201123054610",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg/revision/latest?cb=20201124094800",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg/revision/latest?cb=20160303223223",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style scoped>
.content {
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}

.comic-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.comic-item {
  background-color: #fff;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 200px;
  text-align: center;
}

.comic-thumb {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}
</style>

<style lang="scss" scoped>
.content {
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}

.comic-list {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.comic-item {
  background-color: #fff;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 200px;
  text-align: center;
}

.comic-thumb {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}
</style>