{#each tasks as task}
    <div>
        <h1 class="text-2xl font-bold underline">
            {task.title}
        </h1>
    </div>
{/each}
  
<style lang="postcss">
</style>

<script lang="ts">
    import {tasks} from "../lib/tasks"
</script>
