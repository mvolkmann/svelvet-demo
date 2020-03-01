<script>
  import _ from '/web_modules/lodash';
  import DateDisplay from './DateDisplay';
  import Foo from './Foo.js';

  import dogs from './dogs.json';
  console.log('dogs =', dogs);

  let name = 'Svelvet';
</script>

<h1>Hello, {_.startCase(name)}!</h1>

<label>
  Name
  <input bind:value={name}>
</label>

<DateDisplay />
<Foo />

<style>
  h1 {
    color: red;
  }
</style>
