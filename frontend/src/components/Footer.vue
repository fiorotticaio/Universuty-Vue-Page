<template>
    
    <footer>
        <div class="content container">
            <address>
                <h3>Departamento de Informática, UFES</h3>
                <p>Av. Fernando Ferrari, 514 - UFES, CT-7<br>
                    Goiabeiras - Vitória, ES - 29075-510<br>
                    BRASIL
                </p>
            </address>
            <ul>
                <li>ufes@gmail.com</li>
                <li>@STI</li>
            </ul>
        </div>
    </footer>
    
</template>


<script>

export default {
    name: 'Footer',
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

footer {
    position: relative;
    height: 33rem;
    opacity: 0.5;

    background: #4A879E;
    display: inline-block;
    width: 100%;
    color: white;
}

footer::before {
    content: '';
    position: absolute;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    background-image: url('../assets/muroUfes.svg');
    background-size: cover;
    background-position: top center;
    opacity: 0.2;
}

footer .content {
    margin-top: 6.2rem;
    margin-left: 3rem;
    font-size: 5rem;
    font-family: Montserrat;
    font-weight: 400;
}

footer .content address {
    margin-bottom: 1.5rem;
}

footer .content h3 {
    margin-bottom: 1.5rem;
    text-decoration: underline;
}

footer div ul {
    margin-left: 2rem;
    list-style: square;
}

</style>