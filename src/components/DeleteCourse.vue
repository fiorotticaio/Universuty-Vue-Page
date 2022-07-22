<template>
    
    <div>
        <h2>Deletar curso</h2>

        <label for="select-couse">Selecione o curso que deseja deletar</label>
        <select id="sel-course" name="sel-course">
            <option value="engComp">Engenharia da computação</option>
            <option value="artes">Artes</option>
            <option value="mat">Matemática</option>
            <option value="filo">Filosofia</option>
        </select>

        <!-- v-if="{{ selectCourse }}" -->
        <input type="submit" value="Deletar">



    </div>
    
</template>


<script>

export default {
    name: 'DeleteCourse',
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

input[type=submit] {
    display: block;
    width: 20%;
    background-color: #f82121;
    color: white;
    padding: 1.4rem 2.0rem;
    margin: 3rem auto;
    border: none;
    border-radius: 0.4rem;
    cursor: pointer;
}

</style>