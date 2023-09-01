<script>
  import Welcome from '$lib/components/index/welcome.svelte';
  import CallToAction from '$lib/components/index/calltoaction.svelte';
  import Hour from '$lib/components/index/hour.svelte';
  import Fund from '$lib/components/index/funds.svelte';
  import Member from '$lib/components/index/member.svelte';
  import Event from '$lib/components/index/event.svelte';
  import Announcement from '$lib/components/index/announcement.svelte';
</script>

<svelte:head>
  <title>Circle K International at Cal State Fullerton</title>
</svelte:head>

<Welcome />
<CallToAction />
<Announcement />
<Event />
<Hour />
<Fund />
<Member />
