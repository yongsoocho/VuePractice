<template>
<v-navigation-drawer>
	 <v-list-item>
          <v-list-item-content>
            <v-list-item-title>분석 팀 선택</v-list-item-title>
          </v-list-item-content>
	</v-list-item>
	
	<v-divider></v-divider>
	
	<v-list>
		<v-list-item v-for="link in links">
			<v-list-item-icon>
				<v-icon>{{ link.icon }}</v-icon>
			</v-list-item-icon>
			<v-list-item-content>
				<v-list-item-title>{{ link.text }}</v-list-item-title>
			</v-list-item-content>
		</v-list-item>
	</v-list>
</v-navigation-drawer>
</template>

<script>
import { mdiEmoticonAngryOutline } from '@mdi/js';
import { mdiEmoticonHappyOutline } from '@mdi/js';	
import { mdiEmoticonTongueOutline } from '@mdi/js';
	
export default {
	data(){
		return{
			links:[
				{ icon:mdiEmoticonAngryOutline, text:'Angry' },
				{ icon:mdiEmoticonHappyOutline, text:'Happy' },
				{ icon:mdiEmoticonTongueOutline, text:'Funny' },
			],
		}
	},
}
</script>

<style>

</style>