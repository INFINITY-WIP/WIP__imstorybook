<script>
  import { Meta, Template, Story } from "@storybook/addon-svelte-csf";
  import Table from "./index.svelte";
</script>

<Meta
  title="Example/Table"
  component={Table}
/>

<Template let:args>
  <Table {...args} />
</Template>

<Story
  name="default"
/>

