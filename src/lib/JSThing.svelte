<script context="module">
    export class Thing {
        constructor(name) { 
            this.name = name;
        }
    }
</script>

<script>
    export var thing;
</script>

<div>
    <h1>Hello, {thing.name}!</h1>
</div>