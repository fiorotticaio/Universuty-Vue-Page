<template>
  <div>
    <Header />

    <ListBox />

    <NewCourse />

    <EditCourse />

    <!-- <DeleteCourse /> -->

    <!-- <Footer /> -->
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ListBox from './components/ListBox.vue';
import NewCourse from './components/NewCourse.vue';
import EditCourse from './components/EditCourse.vue';

export default {
  name: 'App',
  components: {
    Header,
    ListBox,
    NewCourse, 
    EditCourse,
  },
  data() {
    return {
        
    }
  }
}
</script>