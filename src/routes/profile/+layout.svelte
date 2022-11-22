
<script>
	import { fns, AppShell, Navbar, Header, Title, Divider } from '@svelteuidev/core';
</script>

<AppShell>
	<Navbar slot="navbar">
        <Title order={2}>Profile Title</Title>
	</Navbar>
	<Header slot="header">
        <Title>Profile Header</Title>
	</Header>

	<slot>This is the main content</slot>
</AppShell>