<script>
	import Button from "$lib/button/Button.svelte";
	import Hero from "$lib/hero/Hero.svelte";
	import Snippet from "$lib/snippet/Snippet.svelte";
	import Spacer from "$lib/spacer/Spacer.svelte";
	import Text from "$lib/text/Text.svelte";
</script>

<svelte:head>
	<title>Облачный персональный ИИ-компьютер</title>
</svelte:head>

<Hero exclusionHeight={79}>
	<Text type="h3" align="center">Облачный персональный ИИ-компьютер и диалоговая ОС на основе автономных агентов</Text>
	<Spacer h={20} />
	<div class="flex place-items-center">
		<Button href="/guide" color="secondary-light">Получить свой экземпляр</Button>
		<Spacer w={10} />
		<Button href="/components">Узнать больше</Button>
	</div>
	<Spacer h={20} />
	<div class="hidden md:block">
		<Snippet type="transparent" text="https://ag.prtl.cc" />
	</div>
</Hero>
