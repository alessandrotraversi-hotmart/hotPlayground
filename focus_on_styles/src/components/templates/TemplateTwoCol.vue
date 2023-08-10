<template>
    <header>
        <hot-header />
    </header>
    <main>
        <aside>
            <slot name="aside" />
        </aside>
        <slot name="main" />
    </main>
    <footer>
        <hot-footer />
    </footer>
</template>