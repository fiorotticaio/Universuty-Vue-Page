<template>
  <div>
    <Header />

    <ListBox />

    <NewCourse />

    <EditCourse />

    <DeleteCourse />

    <Footer />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import ListBox from './components/ListBox.vue';
import NewCourse from './components/NewCourse.vue';
import EditCourse from './components/EditCourse.vue';
import DeleteCourse from './components/DeleteCourse.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    ListBox,
    NewCourse, 
    EditCourse,
    DeleteCourse,
    Footer
  },
  data() {
    return {
        
    }
  }
}
</script>