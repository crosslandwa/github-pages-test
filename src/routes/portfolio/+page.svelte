<script lang="ts">
  import { asset } from '$app/paths'

	let { children } = $props();
</script>

<h2>Portfolio</h2>

<ul>
  <li>
    <a href={asset('/Invisible Manchester_0919.pdf')} target="_blank">
      <img
        sizes="148px"
        src={asset('/Danny_edited.jpg')}
        alt="Danny"
        width="148"
        height="137"
        style="object-fit: cover;">
      </a>
  </li>
</ul>