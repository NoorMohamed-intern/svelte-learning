<script>
	import FeedbackList from './components/FeedbackList.svelte'
	import FeedbackStats from './components/FeedbackStats.svelte'
	import FeedbackForm from './components/FeedbackForm.svelte'

</script>

<main class="container">
	<h1 style="text-align: center; text-decoration: underline;"> Simple Svelte App </h1>
	<FeedbackForm />
	<FeedbackStats />
	<FeedbackList />
</main>