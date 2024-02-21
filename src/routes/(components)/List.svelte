<script>
	import Card from '../../lib/Card.svelte';
</script>

<section class={$$restProps.class}>
	<Card
		header="lebih_dari"
		src="/assets/pedagang-more@2x.png"
		footer="pilihan_pedagang"
		color="text-[#F90300]"
	/>

	<Card
		header="tawar_untuk"
		src="/assets/rectangle-7209-1@2x.png"
		footer="<span class='text-lg'>mendapatkan</span>_harga_terbaik"
		color="text-[#1281A1]"
		isShifted
	/>

	<Card
		header="jendela"
		src="/assets/homepage-container@2x.png"
		footer="budaya_lokal"
		color="text-[#009943]"
	/>

	<Card
		header="dukung"
		src="/assets/rectangle-7209@2x.png"
		footer="ekonomi_kerakyatan"
		color="text-[#FF6B00]"
		isShifted
	/>
</section>
