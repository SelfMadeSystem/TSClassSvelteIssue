<script context="module" lang="ts">
    export class Thing {
        constructor(public name: string) { // Unexpected token?
        }
    }
</script>

<script lang="ts">
    export var thing: Thing;
</script>

<div>
    <h1>Hello, {thing.name}!</h1>
</div>