<script lang="typescript">
  import _ from 'lodash';
  //import DateDisplay from './DateDisplay';
  //import Foo from './Foo.js';

  //import dogs from './dogs.json';
  //console.log('dogs =', dogs);

  let name: string = 'Svelvet';

  function add(n1: number, n2: number): number {
    return n1 + n2;
  }

  const sum: string = add(2, '3');
</script>

<h1>Hello, {_.startCase(name)}!</h1>

<label>
  Name
  <input bind:value="{name}" />
</label>

<!--
<DateDisplay />
<Foo />

<div>sum = {sum}</div>
-->
