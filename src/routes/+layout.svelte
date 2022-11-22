<script>
  import { SvelteUIProvider, AppShell, Navbar, Title, Header } from "@svelteuidev/core";
</script>

<SvelteUIProvider>
  <script>
    import {
      fns,
      AppShell,
      Navbar,
      Header,
      Title,
      Divider,
    } from "@svelteuidev/core";
  </script>

  <AppShell>
    <Navbar slot="navbar">
      <Title>Title</Title>
    </Navbar>
    <Header slot="header">
      <Title>Header</Title>
    </Header>

    <slot />
  </AppShell>
</SvelteUIProvider>
