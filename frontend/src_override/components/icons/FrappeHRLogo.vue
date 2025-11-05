<template>
	<img
		:src="logoUrl"
		alt="Frappe HR Logo"
		class="h-full w-full object-contain max-w-[70px] max-h-[70px]"
	/>
</template>

<script setup>
// Place your logo at: frontend/src_override/assets/login-logo.png
import logoUrl from '../../assets/login-logo.png?url'
</script>
