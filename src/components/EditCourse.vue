<template>
    
    <div>
        <h2>Editar curso</h2>

        <label for="select-couse">Selecione um curso</label>
        <select id="sel-course" name="sel-course">
            <option value="engComp">Engenharia da computação</option>
            <option value="artes">Artes</option>
            <option value="mat">Matemática</option>
            <option value="filo">Filosofia</option>
        </select>

        <!-- v-if="{{ selectCourse }}" -->
        <div class="course-data">
            <label for="name">Nome</label>
            <input type="text" id="name" name="courseName" placeholder="{{ Nome do curso }}">
    
            <label for="id">ID</label>
            <input type="text" id="id" name="courseID" placeholder="{{ ID do curso }}">
    
            <label for="code">ID</label>
            <input type="text" id="code" name="courseCode" placeholder="{{ Código do curso }}">
    
            <label for="area">Área do conhecimento</label>
            <select class="data" id="area" name="area">
                <option value="exatas">Exatas</option>
                <option value="biomedicas">Biomédicas</option>
                <option value="humanas">Humanas</option>
            </select>

        </div>

    </div>
    
</template>


<script>

export default {
    name: 'EditCourse',
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

input[type=text], select.data {
    width: 100%;
    padding: 1.2rem 2.0rem;
    margin: 0.8rem 0;
    display: inline-block;
    border: 0.1rem solid #ccc;
    border-radius: 0.4rem;
    box-sizing: border-box;
}

input[type=submit] {
    width: 100%;
    background-color: #4CAF50;
    color: white;
    padding: 1.4rem 2.0rem;
    margin: 0.8rem 0;
    border: none;
    border-radius: 0.4rem;
    cursor: pointer;
}


</style>