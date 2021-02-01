<template>
  <q-page padding class="flex flex-center">
    <div class="row">
     <q-card class="my-card">
      <q-img src="https://cdn.pixabay.com/photo/2018/07/09/13/38/cake-3526158_960_720.jpg" />

      <q-card-section>

        <div class="row no-wrap items-center">
          <div class="col text-h6 ellipsis">
            Dayse Cabral
          </div>
        </div>

        <q-rating v-model="stars" :max="5" size="32px" />
      </q-card-section>

      <q-card-section class="q-pt-none">
        <div class="text-subtitle1">
          Torta de morango
        </div>
        <div class="text-caption text-grey">
          Veja a receita, modo de preparo, tempo e ingredientes aqui.
        </div>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        <q-btn flat round icon="visibility" />
        <q-btn flat color="primary">
          VER
        </q-btn>
      </q-card-actions>
    </q-card>
   </div>
  </q-page>
</template>

<script>
export default {
  // name: 'PageName',
}
</script>
