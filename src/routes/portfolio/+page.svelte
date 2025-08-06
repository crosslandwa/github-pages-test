<script lang="ts">
	import invisibleManchesterPdf from '$lib/assets/Invisible Manchester_0919.pdf';
  import invisibleManchesterImg from '$lib/assets/Danny_edited.jpg';

	let { children } = $props();
</script>

<h2>Portfolio</h2>

<ul>
  <li>
    <a href={invisibleManchesterPdf} target="_blank">
      <img
        loading="lazy"
        sizes="148px"
        id="img_comp-k1ruq8nc"
        src={invisibleManchesterImg}
        alt="Danny_edited.jpg"
        width="148"
        height="137"
        style="object-fit: cover;">
      </a>
  </li>
</ul>