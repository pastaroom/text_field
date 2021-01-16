<template>
  <div class="about">
    <!-- <v-layout align-left>
      <v-btn class="ma-2" small color="primary">Primary</v-btn>
      <v-btn class="ma-2" small color="indigo">Primary</v-btn>
    </v-layout>
    <v-layout align-center>
      <v-btn class="ma-2" small color="primary">Primary</v-btn>
      <v-btn class="ma-2" small color="indigo">Primary</v-btn>
      <v-btn class="ma-2" small color="success">Primary</v-btn>
      <v-btn class="ma-2 right" small color="teal">Primary</v-btn>
    </v-layout>
    <v-row justify='end'>
      <v-col>
        <v-btn>Button 1</v-btn>
        <v-btn>Button 1</v-btn>
        <v-btn>Button 1</v-btn>
      </v-col>
    </v-row> -->
    <!-- <div fluid>
      <div class="text-left">
        <v-btn class="ma-2" small color="primary">Primary</v-btn>
        <v-btn class="ma-2" small color="indigo">Primary</v-btn>
      </div>
      <div class="text-right">
        <v-btn class="ma-2" small color="primary">Primary</v-btn>
        <v-btn class="ma-2" small color="indigo">Primary</v-btn>
        <v-btn class="ma-2" small color="success">Primary</v-btn>
        <v-btn class="ma-2 right" small color="teal">Primary</v-btn>
      </div>
    </div> -->
    <!-- <v-form
      ref="form"
      @submit.prevent="submit"
    >
      <v-container fluid>
        <v-row>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.one"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.two"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.three"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.five"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.six"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-text-field
              v-model="form.seven"
              label="Outlined"
              placeholder="Placeholder"
              outlined
              required
            ></v-text-field>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-flex xs12>
              <v-textarea
                outlined
                shaped
                v-model="form.eight"
                name="input-7-4"
                label="Outline textarea"
                value="The Woodman set to work at once, and so sharp was his axe that the tree was soon chopped nearly through."
                required
              ></v-textarea>
            </v-flex>
          </v-col>
          <v-col
            cols="12"
            md="12"
            lg="6"
          >
            <v-flex xs12>
              <v-textarea
                outlined
                shaped
                v-model="form.nine"
                name="input-7-4"
                label="Outline textarea"
                value="The Woodman set to work at once, and so sharp was his axe that the tree was soon chopped nearly through."
                required
              ></v-textarea>
            </v-flex>
          </v-col>
        </v-row>
      </v-container>
    </v-form> -->
    <v-btn
      color="blue-grey"
      class="ma-2 white--text"
    >
      Upload
      <v-icon right dark>mdi-cloud-upload</v-icon>
    </v-btn>
  </div>
</template>
<script lang="ts">
  import { Component, Vue } from 'vue-property-decorator';

  @Component
  export default class About extends Vue {
  }
</script>

<style scoped>

</style>
