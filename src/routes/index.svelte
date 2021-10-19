<script>

import Calendar from "$lib/Calendar.svelte";

</script>

<h1>
	Geekonical Calendar
</h1>
<div class="calendar-container">
	<div class="calendar-wrapper">
		<Calendar/>
	</div>
</div>
<style lang="scss">
	.calendar-container {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		
		.calendar-wrapper {
			width: 95vw;
			@media (min-width: 1000px) {
				width: 50vw;
			border-radius: 50px;
			background: #e0e0e0;
			box-shadow:  20px 20px 60px #bebebe,
             -20px -20px 60px #ffffff;
			 padding: 2em;
			}

			
		}
	}
</style>