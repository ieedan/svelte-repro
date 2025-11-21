<script>
	import { page } from '$app/state';

	$inspect(page.url.pathname);
</script>

<div class="flex flex-col gap-2">
	<div class="flex items-center gap-2">
		<span class="font-bold">Pathname:</span>
		<span>{page.url.pathname}</span>
	</div>

	<a href="/about">About</a>
</div>
