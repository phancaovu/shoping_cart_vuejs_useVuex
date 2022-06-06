<template>
	<div id="app">
		<div class="container">
		<!-- TITLE : START -->
		<comp-title></comp-title>
		
		<!-- TITLE : END -->

		<div class="row">
			<product-list/>
			<cart-wrapper/>	
		</div>
	</div>



	</div>
</template>

<script>
import CartWrapper from './components/CartWrapper.vue';
import CompTitle from './components/CompTitle.vue';
import ProductList from './components/ProductList.vue';
export default {
  components: { CompTitle, ProductList, CartWrapper },
	name: 'app',
	data () {
		return {
			
		}
	} 
}
</script>

<style>

</style>
