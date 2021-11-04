<script context="module" lang="ts">
    export class Thing {
        constructor(public name: string) {   
        }
    }
</script>

<script lang="ts">
    export var thing: Thing;
</script>

<div>
    <h1>Hello, {thing.name}!</h1>
</div>