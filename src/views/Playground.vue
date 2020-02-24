<template>
  <v-container>
    <v-row>
      <v-col cols="12">
        <v-row class="mb-12">
          <v-col cols="12">
            <h1 class="mb-5">Playground</h1>
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Typography />
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Spacing />
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Buttons />
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Menus />
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Grid />
            <v-divider />
          </v-col>
        </v-row>
        <v-row class="mb-12">
          <v-col cols="12">
            <Card />
            <v-divider />
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
import Typography from '@/components/Typography.vue'
import Spacing from '@/components/Spacing.vue'
import Buttons from '@/components/Buttons.vue'
import Menus from '@/components/Menus.vue'
import Grid from '@/components/Grid.vue'
import Card from '@/components/Card.vue'

export default {
  components: {
    Typography,
    Spacing,
    Buttons,
    Menus,
    Grid,
    Card
  }
}
</script>
