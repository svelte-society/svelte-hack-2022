<div class="blob-a">
	<svg
		width="100%"
		height="100%"
		viewBox="0 0 279 886"
		fill="none"
		xmlns="http://www.w3.org/2000/svg"
	>
		<path
			class="bg"
			d="M111.996 283.476C-21.6631 160.103 72.7179 127.61 -44.1519 0.368652L-43.3481 845.202C71.1043 780.084 295.029 657.271 277.168 538.606C254.841 390.274 245.654 406.849 111.996 283.476Z"
			fill="var(--brand-b)"
		/>
		<path
			class="fg"
			d="M109.873 324.213C-23.7861 200.84 70.5948 168.347 -46.2749 41.1055L-45.4711 885.938C68.9813 820.821 292.906 698.008 275.045 579.343C252.718 431.011 243.531 447.586 109.873 324.213Z"
			fill="var(--brand-c)"
		/>
	</svg>
</div>

<style lang="scss">
	.blob-a {
		width: var(--size, 279px);
	}

	:global(:root[theme='dark'] .blob-a) {
		filter: saturate(1.25) brightness(0.5) contrast(1.25);
	}
</style>
