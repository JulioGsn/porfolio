<script lang="ts">
    export let iconUrl: string;
    export let description: string;
</script>
<div class="flex items-center flex-col gap-1">
    <img src={iconUrl} alt={description} class="w-14 h-14">
    <div class="text-slate-700 text-sm">
        {description}
    </div>
</div>
