<script lang="ts">
  import { getTest, type Test } from "$lib/test";

  let t: Test = getTest();
</script>

<div>
  Testing type imports. {t.value}
</div>
