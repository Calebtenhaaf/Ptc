<div class="background">
<div class="layout">
    <slot />
    </div>
</div>

<style>
    .background {
        padding: 16px;

        position: absolute;
        inset: 0;

        background-color: darkblue;
    }

    .layout {
        width: 100%;
        max-width: 1024px;
        margin: 0 auto;
    }
</style>

input[type=checkbox] {
    accent-color: red;
}

input[type=radio] {
    accent-color: green;
}

input[type=range] {
    accent-color: rgb(0, 0, 255);
}

progress {
    accent-color: hsl(39, 100%, 50%);
}