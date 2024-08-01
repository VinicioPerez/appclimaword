<template>
    <div class="alerta">
        <slot></slot>
    </div>
</template>

<style>
    .alerta {
        text-align: center;
        margin-bottom: 1.5rem;
        color: var(--error);
        text-transform: uppercase;
        font-weight: 700;
        font-size: 1.8rem;
        padding: .5rem
    }
</style>