<template>
  <v-container
    grid-list-md
    text-xs-center
    fill-height
  >
    <v-layout
      row
      wrap
      align-center
    >
      <v-flex
        xs12
        sm4
        :class="{
          'display-3': $vuetify.breakpoint.smAndUp,
          'red--text': $vuetify.breakpoint.xs
        }"
      >
        Sub component
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  name: 'SubComponent'
}
</script>
