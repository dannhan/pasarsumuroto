<script>
	import Card from '../../lib/Card.svelte';
</script>

<section class={$$restProps.class}>
	<Card
		header="lebih_dari"
		image="pedagang-more@2x"
		footer="pilihan_pedagang"
		color="text-[#F90300]"
	/>

	<Card
		header="tawar_untuk"
		image="rectangle-7209-1@2x"
		footer="<span class='text-lg'>mendapatkan</span>_harga_terbaik"
		color="text-[#1281A1]"
		isShifted
	/>

	<Card
		header="jendela"
		image="homepage-container@2x"
		footer="budaya_lokal"
		color="text-[#009943]"
	/>

	<Card
		header="dukung"
		image="rectangle-7209@2x"
		footer="ekonomi_kerakyatan"
		color="text-[#FF6B00]"
		isShifted
	/>
</section>
