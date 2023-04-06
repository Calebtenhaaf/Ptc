<script>
	import Question from "../components/question.svelte";
import Score from "../components/score.svelte";

</script>
<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<Score score={14} />

<Question number ={1}>
    answer1="First answer"
    answer2="second answer"
    answer3="Third answer"
    answer4="All the above"
    This is my question
</Question>

<Question number ={2}>
    answer1="First answer"
    answer2="second answer"
    answer3="Third answer"
    answer4="All the above"
    This is my question
</Question>

<Question number ={3}>
    answer1="First answer"
    answer2="second answer"
    answer3="Third answer"
    answer4="All the above"
    This is my question
</Question>

<Question number ={4}>
    answer1="First answer"
    answer2="second answer"
    answer3="Third answer"
    answer4="All the above"
    This is my question
</Question>

