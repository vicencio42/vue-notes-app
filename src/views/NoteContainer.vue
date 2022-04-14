<template>
  <div class="note-container">
    <NoteSelectors />
    <div class="note-editor">
      <p class="note-editor-info">Timestamp here...</p>
      <textarea class="note-editor-input">
          First note...

          Note text here...
        </textarea
      >
    </div>
  </div>
</template>

<script>
import NoteSelectors from "./NoteSelectors.vue";

export default {
  components: {
    NoteSelectors,
  },
};
</script>
