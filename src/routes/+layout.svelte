<div class="background">
<div class="layout">
    <div class="header"></div>
    <div class="content"></div>
    <score score={0} />
    <slot />
    </div>
</div>

<style>
    .background {
        padding: 16px;
        display: grid;
        position: absolute;
        inset: 0;

        background-color: var(--color-purle);
    }

    .layout {
        width: 100%;
        max-width: 1024px;
        margin: 0 auto;

        display: grid;
        grid-template-rows: auto 1fr;
        align-items: center; 
    }

    .header,
    .content {
        background-color: white;
        border: 4px solid black;
        padding: 12px 24px;
    }

    .header {
        display: flex;
        justify-content: space-between; 
    }
</style>