<template>
    
    <div>
        <h2>Cadastrar curso</h2>


        <div class="form">
            <form action="/action_page.php">
                <label for="name">Nome</label>
                <input type="text" id="name" name="courseName" placeholder="Nome do curso">

                <label for="id">ID</label>
                <input type="text" id="id" name="courseID" placeholder="ID do curso">

                <label for="code">ID</label>
                <input type="text" id="code" name="courseCode" placeholder="Código do curso">

                <label for="area">Área do conhecimento</label>
                <select id="area" name="area">
                    <option value="exatas">Exatas</option>
                    <option value="biomedicas">Biomédicas</option>
                    <option value="humanas">Humanas</option>
                </select>
            
                <input type="submit" value="Enviar">
            </form>
        </div>


    </div>
    
</template>


<script>

export default {
    name: 'NewCouse',
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

input[type=text], select {
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

input[type=submit]:hover {
    background-color: #45a049;
}

div.form {
    border-radius: 0.5rem;
    background-color: #95a5a6;
    padding: 2rem;
}

</style>
