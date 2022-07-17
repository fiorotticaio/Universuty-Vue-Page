<template>
    <header>
        <img src="../assets/logo-ufes.png" />
        <nav>
            <ul>
                <li><a href="">LISTAR</a></li>
                <li><a href="">CRIAR</a></li>
                <li><a href="">EDITAR</a></li>
                <li><a href="">DELETAR</a></li>
            </ul>
        </nav>
    </header>
</template>


<script>
export default {
  name: 'Header',
  data() {
        return {
        
        }
  }
}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&display=swap');

header {
    background: linear-gradient(to right, #54a0ff, #0abde3);
    height: 10rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    padding: 0 2rem;
}

img {
    width: 10rem;;
    height: auto;
}

ul {
    display: flex;
    list-style: none;
    margin: 5rem;
    padding: 0;
    gap: 2rem;
}

a {
    font-size: 2rem;
    font-family: Montserrat;
    font-weight: 400;
    color: #222f3e; 
    text-decoration: none;
    
    transition: all 0.4s;
}

a:hover {
    font-weight: 700;;
}

</style>
