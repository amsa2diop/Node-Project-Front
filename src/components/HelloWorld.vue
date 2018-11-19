<template>
  <v-container>
    <v-layout
      text-xs-center
      wrap
      justify-center
    >
      <v-flex py-5 mt-5 xs12>
        <v-img
          :src="require('../assets/1024px-Red_Cross_icon.svg.png')"
          class="my-2"
          contain
          height="150"
        ></v-img>
      </v-flex>

      <v-flex pb-5 xs12>
        <h1 class="display-1 font-arial">
          Welcome to Warn Me 
        </h1>
      </v-flex>

      <v-flex md6>
        <v-card class="elevation-10">
          <v-card-text>
            <v-form>
              <v-text-field prepend-icon="person_outline" name="login" label="E-mail" type="text" ></v-text-field>

              <v-text-field id="password" prepend-icon="lock" name="password" label="Senha" type="password"></v-text-field>
            </v-form>
          </v-card-text>
          <v-card-actions>
            <v-btn round block color="success">Login</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>

    </v-layout>
  </v-container>
</template>

<script>
  export default {
    data: () => ({

    })
  }
</script>

<style>

</style>
