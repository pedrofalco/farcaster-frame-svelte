<script>
    import "/src/style.css";
    import { PUBLIC_BASE_URL } from '$env/static/public';
	import Front from "$lib/components/Front.svelte";
</script>

<svelte:head>
    <title>Farcaster Frame made in Svelte</title>

    <meta property="of:accepts:xmtp" content="2024-02-01" />
    <meta property="og:image" content="{PUBLIC_BASE_URL}/image1.png" />
    <meta property="fc:frame" content="vNext" />
    <meta property="fc:frame:image" content="{PUBLIC_BASE_URL}/image1.png" />
    <meta property="fc:frame:image:aspect_ratio" content="1:1"/>

</svelte:head>

<Front/>