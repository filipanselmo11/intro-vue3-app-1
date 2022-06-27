<template>
  <div>
    <h2>Filter LearnVue Articles</h2>
    <input type="text" placeholder="Filter Search" v-model="query" />
    <br />
    <br />
    <button @click="reset">Reset</button>
    <search-results :query="query"></search-results>
  </div>
</template>

<script>
import SearchResults from "./SearchResults.vue";
export default {
  name: "NovoComponent",
  components: { SearchResults },
  data() {
    return {
      query: "",
    };
  },
  methods: {
    reset() {
      this.query = "";
    },
  },
};
</script>
