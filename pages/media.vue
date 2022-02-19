
<template>
  <div>


     

    <modal name="my-modal">
      <div class="modal-content">
        <h2>It work's!</h2>

        <button @click="$modal.hide('my-modal')">Close it</button>
      </div>
    </modal>
  </div>
</template>

<script>
export default {
  components: {},


};
</script>

<style>
header,
h2 {
  margin-bottom: 20px;
}
.modal-content {
  height: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>

</template>

<script>


</script>

<style>

</style>
