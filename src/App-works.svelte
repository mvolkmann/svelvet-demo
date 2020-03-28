<script>
  import _ from 'lodash';

  let name = 'Svelvet';
</script>

<h1>Hello, {_.startCase(name)}!</h1>

<label>
  Name
  <input bind:value="{name}" />
</label>
