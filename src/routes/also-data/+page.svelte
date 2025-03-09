<script lang="ts">
  // #1120: This fails the lint check on Linux but not on Windows.
  // #1121: The destructured prop is still `data` so the failure feels like a false positive.
  let { data: pageData } = $props()
  let data = $derived(pageData)
</script>

<code>{data}</code>
