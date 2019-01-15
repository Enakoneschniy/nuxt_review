<template>
  <v-container grid-list-md text-xs-center>
    <v-layout row wrap>
      <CompanyCard/>
      <CompanyCard/>
      <CompanyCard/>
    </v-layout>
  </v-container>
</template>

<script>
  import CompanyCard from "../../components/CompanyCard";
  export default {
    components: { CompanyCard }
  }
</script>
