<script lang="ts">
  // TS and TS2 don't work, but JS does. Why?
  import ThingConponent, { Thing } from "./lib/TSThing.svelte";

  var thing = new Thing("world");
</script>

<ThingConponent {thing} />

