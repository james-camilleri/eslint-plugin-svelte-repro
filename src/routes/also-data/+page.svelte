<script lang="ts">
  let { data: pageData } = $props()
  let data = $derived(pageData)
</script>

<code>{data}</code>
