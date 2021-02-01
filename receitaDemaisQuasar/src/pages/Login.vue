<template>
  <q-page padding class="flex flex-center row">
    <div class="row col-12">
     <q-card bordered class="bg-grey-1 col-12">
      <q-card-section>
        <div class="row items-center no-wrap">
          <div class="col-12">
            <div class="flex flex-center text-h6">Acesse sua conta</div>
          </div>

        </div>
      </q-card-section>

      <q-card-section>
        <div>
          <q-input type="email" filled outlined v-model="text" label="Digite seu e-mail" />
          <q-input type="password" filled outlined v-model="text" label="Digite sua senha" />
          <div class="text-caption q-mt-sm">
          </div>
        </div>
      </q-card-section>

      <q-separator />

      <q-card-actions>
        <div class="flex flex-center col-12">
          <q-btn color="primary" label="Cadastre-se" to="/controle/sign-up"></q-btn>
          <q-btn color="primary" label="enviar" />
        </div>
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
