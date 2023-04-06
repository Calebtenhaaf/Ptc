<script>
    export let number =1;

    export let answer1 = "";
</script>

<div>
    <p> {number}.  <slot /></p>

    <label for="q{number}a"><input type="radio" name="q{number}a" id="q{number}a" value="a"
        />
        A: {answer1}
    </label>
</div>

<label for="q{number}b"><input type="radio" name="q{number}b" id="q{number}b" value="b"
    />
    B: {answer1}
</label>

<label for="q{number}c"><input type="radio" name="c{number}c" id="q{number}c" value="c"
    />
    C: {answer1}
</label>

<label for="q{number}d"><input type="radio" name="q{number}d" id="q{number}d" value="d"
    />
    D: {answer1}
</label>

<scripts>
    export let answer = false;
</scripts>
{#if answer1}

<p>
    Correct!
</p>

<p>
    Nope, not that one
</p>

{/if}
