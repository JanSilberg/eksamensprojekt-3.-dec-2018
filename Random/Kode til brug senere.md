    <!-- Knap lavetil at kunne gå en side tilbage -->
    <a id="back" href="javascript:history.back()">
        <img src="Images/back.png" alt="Pil til at gå tilbage">
    </a>



<!-- Dette er menu 2 (skal nok ikke bruges) -->
<div id="menu">
    <a href="maintenance.html">Min profil</a>
    <a href="maintenance.html">Mine ønsker</a>
    <a href="maintenance.html">Julekalender</a>
    <a href="maintenance.html">Club BR</a>
</div>



#menu {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    position: fixed;
    bottom: 1%;
    justify-self: center;
    text-align: center;
    width: 100%;
    align-self: center;
    z-index: 2;
}

#menu a {
    text-decoration: none;
    padding-top: 23%;
    padding-bottom: 23%;
    color: white;
    font-size: 4vw;
}