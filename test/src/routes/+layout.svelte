<style>
    @import url('https://fonts.googleapis.com/css2?family=M+PLUS+Rounded+1c:wght@100;300;400;500;700;800&display=swap');
    main{
        background-color:#272727;
    } 
    div{
        width: 100vw;
        padding-top: 1rem;
        padding-bottom: 1rem;
        background-color:rgb(29, 32, 33);
        color: #E7E7E7;
        font-family: 'M PLUS Rounded 1c', sans-serif;
        display:flex;
        text-align: center;

    }
    a{
        margin: auto;
        text-decoration: none;
        transition: all ease-in-out 400ms;
        color: #6D67E4;
    }
    a:hover{
        color: #453C67;
    }
    :global(body) {
        background-color: #181A1B;
    }
</style>
<div class="flex alight-center text-center ">
    <a href="/">Home</a>
    <a href="/About">About</a>
    <a href="/Contact">Contact</a>
</div>

<slot />
