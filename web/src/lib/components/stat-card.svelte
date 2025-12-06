<script lang="ts">
    import { Badge } from "$lib/components/ui/badge/index.js";
    import * as Card from "$lib/components/ui/card/index.js";
</script>
<div
        class="lg:grid-cols-2 xl:grid-cols-4 grid grid-cols-1 gap-4 px-4 lg:px-6"
>
    <Card.Root>
        <Card.Header>
            <Card.Title>TV shows</Card.Title>
        </Card.Header>
        <Card.Content>
            <p>Card Content</p>
        </Card.Content>
        <Card.Footer>
            <Card.Description>Total count of added TV shows</Card.Description>
        </Card.Footer>
    </Card.Root>
    <Card.Root>
    <Card.Header>
            <Card.Title>Episodes</Card.Title>
        </Card.Header>
        <Card.Content>
            <p>Card Content</p>
        </Card.Content>
        <Card.Footer>
            <Card.Description>Total count of downloaded episodes</Card.Description>
        </Card.Footer>
    </Card.Root>
    <Card.Root>
        <Card.Header>
            <Card.Title>Movies</Card.Title>
        </Card.Header>
        <Card.Content>
            <p>Card Content</p>
        </Card.Content>
        <Card.Footer>
            <Card.Description>Total count of movies</Card.Description>
        </Card.Footer>
    </Card.Root>
    <Card.Root>
        <Card.Header>
            <Card.Title>Torrents</Card.Title>
        </Card.Header>
        <Card.Content>
            <p>Card Content</p>
        </Card.Content>
        <Card.Footer>
            <Card.Description>Total count of torrents/NZBs</Card.Description>
        </Card.Footer>
    </Card.Root>
</div>