<section class="hero">
    <div class="hero-background" >
        <img src="https://lindastade.com/wp-content/uploads/2022/10/ShutterstockBasic_489605152-1280x640.jpg" alt="">
    </div>
        <img src="https://www.souepl.cz/wp-content/uploads/2016/10/logo_stredni-1.jpg" alt="">

    <h1>Střední odborné učiliště, elektrotechnické Plzeň</h1>

    <p>Pojďte stavět vaší budoucnost u nás na škole, kde propojujeme praxi se vzděláváním</p>

    <div class="hero-buttons">
        <a href="/about">Login</a>
        <a href="/" id="ghost">About</a>
    </div>
    
</section>
<section class="dlasistrana">
    <h2 class="nadpis2">Moderní škola pro budoucnost vašich dětí</h2>
    <div class="obecnyinfo">
        <img  class="obrazek2" src="https://1gr.cz/fotky/lidovky/18/104/c460/APE77041a_shutterstock_388657198.jpg" alt="">
        <p class="popis">Naše škola je místem, kde se děti rozvíjejí nejen akademicky, ale také osobnostně. Klíčem k úspěchu je pro nás individuální přístup a inovativní vzdělávací metody, které podporují kreativitu, kritické myšlení a samostatnost.</p>
    </div>
</section>

<style>
    .nadpis2{
        text-align: center;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-weight: 300;
        text-align: center;
        color: white;
        font-size: 50px;
    }
    
    .obecnyinfo{
        display: flex;
        gap: 25px;
        justify-content: center;
        align-items: center;
        color: white;
        
    }
    
    .obrazek2{
        width: 600px;
        height: auto;
        margin-left: 25px;
        margin:25px;
        border-radius: 25px;
        transition: ease 0.5s;
        box-shadow: 20px 20px rgb(93, 176, 206);
    }

    
    
    .popis{
        width: 600px;
        font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-size: 35px;
        text-align: center;
    }

    .dlasistrana{
        height: 600px;    
        background-color: rgb(136, 143, 182);
        padding: 20px;
    
    }

    .hero {
        width: 100%;
        min-height: calc(100vh - 100px);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        position: relative;
        color: white;
    }

    .hero .hero-background{
        position: absolute;
        top: -100px;
        z-index: -1;
        width: 100%;
        height: 100vh;
        background-color: rgba(72, 72, 80, 0.631);
    }

    .hero .hero-background img{
        width: 100%;
        height: 100%;
        z-index: -1;
        object-fit: cover;
        mix-blend-mode: darken;
    }


    .hero img {
        width: 250px;
    }

    .hero-buttons {
        display: flex;
        gap: 36px;
    }

    .hero-buttons a {
        color: white;
        background-color: rgb(44, 158, 59);
        text-decoration: none;
        width: 150px;
        height: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
        border-radius: 10px;
        font-weight: 500;
        font-family: Arial, Helvetica, sans-serif;
        transition: ease 0.5s;
    }

    #ghost {
        color: white;
        background: none;
        border: 1px solid white;
        transition: ease 0.5s;
    }

    #ghost:hover {
        color: white;
        background: red;
        border: 1px solid rgba(0, 0, 0, 0);
    }

    .hero-buttons a:hover {
        color: white;
        background: red;
    }
</style>