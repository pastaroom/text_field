<template>
    <div id="app">
      <v-app id="inspire">
        <v-snackbar
          v-model="snackbar"
          absolute
          top
          right
          color="success"
        >
          <span>Registration successful!</span>
          <v-icon dark>
            mdi-checkbox-marked-circle
          </v-icon>
        </v-snackbar>
        <v-form>
          <v-container>
            <v-row>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
                ></v-text-field>
              </v-col>
              <v-col
                cols="12"
                md="12"
                lg="6"
              >
                <v-text-field
                  label="Outlined"
                  placeholder="Placeholder"
                  outlined
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
                    name="input-7-4"
                    label="Outline textarea"
                    value="The Woodman set to work at once, and so sharp was his axe that the tree was soon chopped nearly through."
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
                    outline
                    shaped
                    name="input-7-4"
                    label="Outline textarea"
                    value="The Woodman set to work at once, and so sharp was his axe that the tree was soon chopped nearly through."
                  ></v-textarea>
                </v-flex>
              </v-col>
            </v-row>
          </v-container>
        </v-form>
      </v-app>
  </div>
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'

@Component
export default class extends Vue {
}
</script>

<style scoped>

</style>
