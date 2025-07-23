<script>
	import SectionWrapper from '../../components/SectionWrapper.svelte';
</script>

<main class="flex flex-col">
	<SectionWrapper>
		<div
			class="max-w-[1400px] mx-auto w-full grid grid-cols-1 sm:grid-cols md:grid-cols-4 text-base"
		>
			<div class="flex gap-4 md:col-span-2 p-10">
				<iframe
					src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d14025.658646254333!2d77.0921116!3d28.4971695!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x390d19b66c8c2f21%3A0xb8120a4412f7ea62!2sWeWork%20Forum!5e0!3m2!1sen!2sin!4v1709483384959!5m2!1sen!2sin"
					width="600"
					height="450"
					title="gmaps-registered-office"
					style="border:0;"
					allowfullscreen=""
					loading="lazy"
					referrerpolicy="no-referrer-when-downgrade"
				></iframe>
			</div>
			<div class="flex flex-col md:col-span-2 p-10">
				<h1>Registered Office</h1>
				<h3>C/O. WeWork DLF Forum,</h3>
				<h3>HD-256,</h3>
				<h3>Cybercity, Phase III,</h3>
				<h3>DLF Qe, Gurugram - 122002</h3>
				<h3>Haryana, India</h3>
				<h3>Mail: <a href="mailto:pmrs9673@gmail.com">contactus@palanhaar.in</a></h3>
				<h3>Phone: <a href="tel:+919487859673"> +919487859673</a></h3>
				<h3>
					<a href="https://www.mappls.com/r3pnuk" target="_blank">Mappls: Get Directions &#8593;</a>
				</h3>
			</div>
		</div>
	</SectionWrapper>
</main>

<style>
    main {
        background: linear-gradient(90deg, #f9f9f9 0%, #fffbe6 100%);
        min-height: 80vh;
    }
    .grid {
        box-shadow: 0 4px 16px rgba(44, 62, 80, 0.08);
        border-radius: 16px;
        border: 1px solid #f0e6d2;
        background: rgba(255,255,255,0.8);
    }
    h1 {
        font-size: 2rem !important;
        font-weight: 900 !important;
        text-decoration-line: underline;
        margin: 10px 0 40px 0;
        color: #2d3e50;
        letter-spacing: 1px;
    }
    h3 {
        font-size: 1.15rem !important;
        margin: 8px 0;
        color: #444;
        font-weight: 500;
    }
    a {
        font-size: 1.15rem !important;
        text-decoration-line: underline;
        color: #2563eb;
        transition: color 0.2s;
    }
    a:hover {
        color: #fbbf24;
    }
    iframe {
        border-radius: 12px;
        box-shadow: 0 2px 8px rgba(44,62,80,0.07);
        border: 1px solid #e0e6ed;
    }
    @media (max-width: 768px) {
        .grid {
            padding: 1rem;
        }
        iframe {
            width: 100%;
            height: 300px;
        }
    }
</style>
