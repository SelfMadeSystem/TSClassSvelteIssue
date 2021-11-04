<script context="module" lang="ts">
    export class Thing {
        public name: string;
        constructor(name: string) {
            this.name = name;
        }
    }
</script>

<script lang="ts">
    export var thing: Thing;
</script>

<div>
    <h1>Hello, {thing.name}!</h1>
</div>