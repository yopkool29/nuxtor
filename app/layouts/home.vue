<template>
	<div>
		<SiteNavbar class="fixed w-full" />
		<SiteSidebar />

		<div class="relative overflow-hidden px-6 lg:px-8">
			<DesignTopBlob />
			<DesignBottomBlob />

			<slot />
		</div>
	</div>
</template>
