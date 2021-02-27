<template>
<v-toolbar>
	<img src="@/assets/PL.png"/>
	<v-toolbar-title class="mx-1">
		<span class="text-h4 black--text">PL MASTER</span>
	</v-toolbar-title>
	<v-spacer></v-spacer>
	<v-toolbar-items>
		<v-btn text plain  class="text-h6 black--text mx-4">홈</v-btn>
		<v-btn text plain  class="text-h6 black--text mx-4">팀분석</v-btn>
		<v-btn text plain  class="text-h6 black--text mx-4">인공지능</v-btn>
		<v-btn text plain  class="text-h6 black--text mx-4">게시판</v-btn>
	</v-toolbar-items>
</v-toolbar>
</template>

<script>
import { mdiLogin } from '@mdi/js';
import { mdiLogout } from '@mdi/js';	
	
export default {
	data(){
		return{
			mdiLogin:mdiLogin,
			mdiLogout:mdiLogout,
		}
	},
}
</script>

<style scoped>
	
</style>