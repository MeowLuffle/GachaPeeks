<script lang="ts">
	import { base } from '$app/paths';
	import background from '$lib/assets/merged bg.png';
	import museofinspo from '$lib/assets/museofinspo.png';
	import mechasetv1 from '$lib/assets/mechasetv1.png';
	import halloweennight from '$lib/assets/halloweennight.png';
	import mechasetbunv1 from '$lib/assets/mechasetbunv1.png';
	import springsinvitation from '$lib/assets/springsinvitation.jpg';
</script>

<!-- Main Container with Background Image -->
<div
	class="w-full"
	style="position: relative; width: 1080px; height: 1400px; background: url({background}); background-size: cover; margin: auto;"
>
	<!-- Each event box represents a clickable area -->

	<!-- Limited Shop - Muse of Inspiration -->
	<div class="event-box" style="left: 22px; top: 528px; width: 297px; height: 59px">
		<div class="tooltip">
			<img src={museofinspo} alt="Limited Shop - Muse of Inspiration" />
		</div>
	</div>

	<!-- SALE - Mechanical Song -->
	<div class="event-box" style="left: 286px; top: 608px; width: 379px; height: 31px">
		<div class="tooltip">「 ✦ discount store sale ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Hunt Task - Magnifiers For Prizes -->
	<div class="event-box" style="left: 735px; top: 606px; width: 250px; height: 55px">
		<div class="tooltip">
			/\___/\<br />
			꒰ ˶• ༝ - ˶꒱<br />
			./づ~ ☕<br /> exchange for prizes <br /> ╰ʚ tba ₊⊹
		</div>
	</div>

	<!-- Shopaholic Login -->
	<div class="event-box" style="left: 117px; top: 644px; width: 411px; height: 34px">
		<div class="tooltip">「 ✦ free goodies login ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Limited 5-star Gacha - Mecha Era -->
	<div class="event-box" style="left: 162px; top: 685px; width: 642px; height: 31px">
		<div class="tooltip">
			<img src={mechasetv1} alt="Limited 5-star Gacha - Mecha Era" />
		</div>
	</div>

	<!-- Black Friday - Fashion Sale -->
	<div class="event-box" style="left: 425px; top: 752px; width: 379px; height: 34px">
		<div class="tooltip">「 ✦ discount store sale ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Makeup Gacha - Rebellious Elegance -->
	<div class="event-box" style="left: 23px; top: 767px; width: 296px; height: 58px">
		<div class="tooltip">💄 makeup gacha 💋 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Gacha Flashback - Night of Halloween -->
	<div class="event-box" style="left: 596px; top: 799px; width: 462px; height: 58px">
		<div class="tooltip">
			<img src={halloweennight} alt="Gacha Flashback - Night of Halloween" />
		</div>
	</div>

	<!-- Mecha Era - Gacha Login Event -->
	<div class="event-box" style="left: 163px; top: 860px; width: 641px; height: 36px">
		<div class="tooltip">
			<img src={mechasetbunv1} alt="Mecha Era - Gacha Login Event" />
			𖹭──── 15 free gacha tickets ────𖹭
		</div>
	</div>

	<!-- Flashback - Spring's Invitation -->
	<div class="event-box" style="left: 91px; top: 899px; width: 333px; height: 58px">
		<div class="tooltip">
			<img src={springsinvitation} alt="Flashback - Spring's Invitation" />
		</div>
	</div>

	<!-- Interstellar Login -->
	<div class="event-box" style="left: 495px; top: 901px; width: 443px; height: 29px">
		<div class="tooltip">「 ✦ free goodies login ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Limited Shop - Winter Sonata -->
	<div class="event-box" style="left: 700px; top: 936px; width: 334px; height: 57px">
		<div class="tooltip">
			<img
				class="small"
				style="width: 50px; height: auto; image-rendering: pixelated;"
				src="https://64.media.tumblr.com/40fe189f479f20fa65b7fce9873cfd99/tumblr_inline_p7l2m6DUKr1rhwzwl_75sq.gifv"
				alt="Cute Pumpkin Cat"
			/>
			<br />「 ✦ limited sale ✦ 」<br /> ╰ʚ tba ₊⊹
		</div>
	</div>

	<!-- Black Friday - Fantasy Sale -->
	<div class="event-box" style="left: 530px; top: 996px; width: 377px; height: 30px">
		<div class="tooltip">「 ✦ discount store sale ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Makeup Gacha - Fearless Vanguard -->
	<div class="event-box" style="left: 286px; top: 1029px; width: 379px; height: 57px">
		<div class="tooltip">💄 makeup gacha 💋 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Hunt Task - Gears For Prizes -->
	<div class="event-box" style="left: 287px; top: 1112px; width: 274px; height: 56px">
		<div class="tooltip">
			/\___/\<br />
			꒰ ˶• ༝ - ˶꒱<br />
			./づ~ ☕<br /> exchange for prizes <br /> ╰ʚ tba ₊⊹
		</div>
	</div>

	<!-- Makeup Gacha - Dual Charm -->
	<div class="event-box" style="left: 700px; top: 1107px; width: 334px; height: 57px">
		<div class="tooltip">💄 makeup gacha 💋 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- SALE - Star Era -->
	<div class="event-box" style="left: 840px; top: 1170px; width: 218px; height: 52px">
		<div class="tooltip">「 ✦ discount store sale ✦ 」<br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Deco Pack - Synthetic Veins -->
	<div class="event-box" style="left: 286px; top: 1197px; width: 379px; height: 29px">
		<div class="tooltip">🖤 black gem decoration 💎 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Flashback Gacha Login Event -->
	<div class="event-box" style="left: 595px; top: 1228px; width: 462px; height: 56px">
		<div class="tooltip">
			<img src={halloweennight} alt="Flashback Gacha Login Event" />
			𖹭──── free gacha tickets ────𖹭 <br />
			❗previously claimed gacha rewards can't be claimed again❗
		</div>
	</div>

	<!-- Deco Pack - Maximalist Aesthetics -->
	<div class="event-box" style="left: 23px; top: 1280px; width: 296px; height: 57px">
		<div class="tooltip">🖤 black gem decoration 💎 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<!-- Deco Pack - Beneath the Car's Shadow -->
	<div class="event-box" style="left: 700px; top: 1286px; width: 334px; height: 77px">
		<div class="tooltip">🖤 black gem decoration 💎 <br /> ╰ʚ tba ₊⊹</div>
	</div>

	<script>
		// Select all event boxes
		const eventBoxes = document.querySelectorAll('.event-box');

		eventBoxes.forEach((box) => {
			const tooltip = box.querySelector('.tooltip');

			// On click (for mobile), toggle tooltip visibility
			box.addEventListener('click', (event) => {
				event.stopPropagation(); // Prevents triggering document click listener

				// Remove active class from all tooltips
				document.querySelectorAll('.tooltip.active').forEach((activeTooltip) => {
					activeTooltip.classList.remove('active');
				});

				// Toggle current tooltip
				tooltip.classList.toggle('active');
			});

			// On hover (for desktop), remove active class from all tooltips and show only the current
			box.addEventListener('mouseenter', () => {
				document.querySelectorAll('.tooltip.active').forEach((activeTooltip) => {
					activeTooltip.classList.remove('active');
				});
				tooltip.classList.add('active');
			});

			// Remove tooltip on mouse leave (for desktop)
			box.addEventListener('mouseleave', () => {
				tooltip.classList.remove('active');
			});
		});

		// Hide tooltip when clicking outside any event box (for mobile)
		document.addEventListener('click', () => {
			document.querySelectorAll('.tooltip.active').forEach((activeTooltip) => {
				activeTooltip.classList.remove('active');
			});
		});
	</script>
</div>

<style>
	/* Styling for clickable areas */
	.event-box {
		position: absolute;
		cursor: pointer;
		border: 1px solid transparent;
		transition: border-color 0.2s;
	}

	.event-box:hover {
		border-color: #00ffff; /* Change to your preferred color */
	}

	/* Tooltip styling */
	.tooltip {
		display: none;
		position: absolute;
		background-color: rgba(0, 0, 0, 0.8);
		color: #fff;
		padding: 10px;
		border-radius: 5px;
		width: 200px;
		text-align: center;
		z-index: 10;
		opacity: 0; /* Set initial opacity to 0 for fade-in effect */
		transition:
			opacity 0.7s ease,
			transform 0.7s ease; /* Smooth transition */
	}

	.event-box:hover .tooltip {
		display: block;
		opacity: 1; /* Fully opaque when hovered */
		transform: translateY(-100%);
		margin-top: -10px;
	}

	/* Specific styling for tooltips containing images */
	.tooltip img {
		margin-top: 5px;
		width: 100%; /* Scale image to fit within tooltip */
		height: auto;
		border-radius: 5px;
	}

	.tooltip:has(img:not(.small)) {
		width: 450px; /* Wider tooltip only if it contains an image */
	}

	.event-box:hover .tooltip {
		display: block;
		transform: translateY(-100%); /* Position tooltip above the box */
		margin-top: -10px; /* Small gap between box and tooltip */
	}
</style>
