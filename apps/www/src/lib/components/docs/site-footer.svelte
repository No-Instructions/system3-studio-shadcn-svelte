<script lang="ts">
	import { siteConfig } from "$lib/config/site.js";
</script>

<footer class="py-6 md:px-8 md:py-0">
	<div class="container flex flex-col items-center justify-between gap-4 md:h-24 md:flex-row">
		<div class="flex flex-col items-center gap-4 px-8 md:flex-row md:gap-2 md:px-0">
			<p class="text-center text-sm leading-loose text-muted-foreground md:text-left">
				Built by
				<a
					href={siteConfig.links.noInstructionsWeb}
					target="_blank"
					rel="noreferrer"
					class="font-medium underline underline-offset-4"
				>
					No Instructions</a
				> on
				<a
					href={siteConfig.links.shadUiWeb}
					target="_blank"
					rel="noreferrer"
					class="font-medium underline underline-offset-4"
				>
					shadcn/ui</a
				>, which was
				<a
					href={siteConfig.links.shadSvelteWeb}
					target="_blank"
					rel="noreferrer"
					class="font-medium underline underline-offset-4"
				>
					ported to Svelte</a
				> by
				<a
					href={siteConfig.links.huntaTwitter}
					target="_blank"
					rel="noreferrer"
					class="font-medium underline underline-offset-4"
				>
					huntabyte</a
				>. The
				<a
					href={siteConfig.links.shadSvelteGithub}
					target="_blank"
					rel="noreferrer"
					class="font-medium underline underline-offset-4"
				>
					source</a
				> is open.	
			</p>
		</div>
	</div>
</footer>
