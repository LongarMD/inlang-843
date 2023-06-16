<script lang="ts">
    import type { PageData } from './$types';
    import { i } from '@inlang/sdk-js'
    
    export let data: PageData;
</script>

<div>
    {i('foo')}
</div>
<div>
    text
</div>