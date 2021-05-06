<script>
	import CharityList from '../components/CharityList.svelte';

	let title = "Charity";
	let charities = ['Charity 1','Charity 2','Charity 3','Charity 4'];

</script>

<style>
	h1{
		font-size: 3em;
		color: #e2071c;
	}
</style>

<!-- <svelte:head>
	<link rel="stylesheet" href="https://cdn.rawgit.com/kimeiga/bahunya/css/bahunya-0.1.3.css" />
</svelte:head> -->

<div>
	<h1>{title}</h1>
	<CharityList {charities}/>
    <CharityList />
</div>



