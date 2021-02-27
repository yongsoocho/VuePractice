<template>
  <v-app>
	<ToolBar></ToolBar>
	<NavigationDrawer></NavigationDrawer>
	  
    <v-main>
      <HelloWorld/>
    </v-main>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
import ToolBar from './components/ToolBar';
import NavigationDrawer from './components/NavigationDrawer';

export default {
  name: 'App',

  components: {
	  HelloWorld,
	  ToolBar,
	  NavigationDrawer
  },

  data: () => ({
    //
  }),
};
</script>
