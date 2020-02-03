<template>
    <div>
        <h2>The counter is currently at: {{ count }}</h2>

        <p>
            <button @click="count += 1">Increment counter</button>
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return { count: 0 }
    }
}
</script>