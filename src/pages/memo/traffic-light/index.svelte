<script>
import Memo from "~/components/memo.svelte";
import { code } from "./traffic-light-machine";
import Content from "./_traffic-light.svelte";
</script>

<Memo {code}>
  <Content />
</Memo>
