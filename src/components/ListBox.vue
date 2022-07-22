<template>
    
    <div>
        <h2>Cursos cadastrados</h2>
        <ul>
            <!-- <li v-for="course in courses">
                <a :href="'/courses/' + course.id">{{ course.name }}</a>
            </li> -->
            <li><a href="">Engenharia da Computação</a></li>
            <li><a href="">Artes</a></li>
            <li><a href="">Matemática</a></li>
            <li><a href="">Filosofia</a></li>
            ...
        </ul>
    </div>
    
</template>


<script>

export default {
    name: 'ListBox',
    data() {
        return {

        }
    },
    methods: {
        
    }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&display=swap');

div {
    font-size: 5rem;

    background-color: #2980b9;
    border: 1px solid #222f3e;
    max-width: 70%;
    min-height: 30rem;

    margin: 2rem auto;
    padding: 2rem;
    border-radius: 2rem;
    box-shadow: #222f3e 0 0 0.6rem;

}

div h2 {
    font-family: Montserrat;
    font-weight: 400;
    color: #24282c; 
    text-decoration: underline;
    text-align: center;
}

ul {
    list-style-image: url('../assets/arrow-list.png');
    margin-left: 5rem;
    margin-top: 2rem;
}

a {
    font-size: 2rem;
    font-weight: 400;
    color: #000000; 
    text-decoration: none;
}

</style>
