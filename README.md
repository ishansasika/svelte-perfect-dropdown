# Svelte Perfect Select

## Install

Install using NPM

```js
npm i svelte-perfect-select
```

Install using YARN

```js
yarn add svelte-perfect-select
```

## How to use

```js
<script>
import Select from 'svelte-perfect-select';

let items = [
  {id:'SL', value:'Sri Lanka'},
  {id:'IND', value:'India'},
  {id:'PAK', value:'Pakistan'}
];
</script>

<body>
<Select options={items}/>
</body>
```
