<template>
  <main>
    <section class="jumbo_section">
      <img src="../assets/jumbotron.jpg" alt="jumbotron" />
    </section>
    <section class="cards_section">
      <div class="container d-flex">
        <h1>CURRENT SERIES</h1>

        <DcCard
          v-for="(dcItem, i) in dcList"
          :key="i"
          :img="dcItem.thumb"
          :title="dcItem.series"
        ></DcCard>

        <!-- <div class="dc_card">
          <div class="card_img">
            <img :src="dcItem.thumb" :alt="dcItem.series"/>
          </div>
          <p>{{dcItem.series}}</p>
        </div>
 -->
      </div>
      <button>LOAD MORE</button>
    </section>
  </main>
</template>


<script>
import jsonData from "../assets/dc-comics.json";
import DcCard from "@/components/DC-card.vue";

export default {
  name: "Main",
  components: {
    DcCard,
  },
  data() {
    return {
      dcList: jsonData,
    };
  },
};
</script>



