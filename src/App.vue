<template>
  <v-app>
    <v-main>
      <full-page
        ref="fullpage"
        :options="options"
        id="fullpage"
        >
        <div class="section">
          <v-container
            class="d-flex
            justify-center
            align-center"
            >
            <div class="text-body-1 white--text">
              The multilingual online translator is a Telegram bot and the part
              of the learning course at JetBrains Academy. It supports all the
              languages provided by the Reverso Context translation service.
            </div>
          </v-container>
        </div>
      <div class="section">
        <v-container
          class="d-flex
          justify-center
          align-center"
          >
          <v-img
            src="./assets/1.png"
            max-width="50%"
          ></v-img>
          <div class="text-h2 white--text">
            Choose any language in a convenient way
          </div>
        </v-container>
      </div>
      <div class="section">
        <v-container
          class="d-flex
          justify-center
          align-center"
          >
          <div class="text-h2 white--text">
            Read examples of the translation used in a specific context
          </div>
          <v-img
            src="./assets/2.png"
            max-width="50%"
          ></v-img>
        </v-container>
      </div>
      <div class="section">
        <v-container
          class="d-flex
          justify-center
          align-center"
          >
          <v-img
            src="./assets/3.png"
            max-width="50%"
          ></v-img>
          <div class="text-h2 white--text">
            Get the regular translation with many options available
          </div>
        </v-container>
      </div>
      <div class="section">
        <v-container
          class="text-center
          d-flex
          justify-center
          align-self-center"
          >
          <v-btn
            rounded
            color="primary"
            dark
            x-large
          >
            Try now
          </v-btn>
        </v-container>
      </div>
    </full-page>
  </v-main>
</v-app>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      options: {
        anchors: ['1', '2', '3', '4'],
        sectionsColor: ['#6c7e87', '#6c7e87', '#6c7e87', '#6c7e87', '#6c7e87'],
      },
    }
  }
}
</script>