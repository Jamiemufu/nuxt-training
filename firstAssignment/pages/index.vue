<template>
  <div class="container">
    <div>
     <ol>
       <li>Create 2 Routes</li>
       <li>Add a button to main page</li>
       <li>Add two links the products page - the two links should go to /products/1 and /products/2</li>
       <li>Output the product id on the /products/:pid page</li>
       <li>i.e products/ => products/1 | products/2</li>
     </ol>
      <button @click="$router.push('/products')">Products Page</button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.title {
  font-family:
    'Quicksand',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
