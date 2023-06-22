# bartender

@media screen and (max-width: 480px) {



  
  .menu li {
    display: block;
    text-align: center;
    margin-bottom: 10px;
  }
  
  .menu li:last-child {
    margin-bottom: 0;
  }
  
  .menu li a {
    padding: 8px;
    font-size: 12px;
  }
  
  .logoDois {
    float: none;
    text-align: center;
    margin-bottom: 10px;
  }
}



 <div class="navbar">
        <div class="logoDois"><img src="assets/logo.png" alt="Logo" style="width: 100px;"></div>
      
        
        <ul class="menu">
          <li><a href="cadastro.html">Cadastro</a></li>
          <li class="dropdown">
            <a href="bartenders.html" class="dropbtn">Portfólio de Bartenders</a>
          </li>
          <li><a href="index.html">Produtos</a></li>
        </ul>
      </div>


      .menu-toggle {
  display: none;
}

.menu {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
}

.menu li {
  display: inline-block;
}

.menu li a {
  display: block;
  color: black;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

.menu li a:hover {
  background-color: #ddd;
}
