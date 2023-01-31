<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" id="brand" href="#">MA Tickets</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon text-light"></span>
      </button>
    </div>
    <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active " aria-current="page" href="#section_1">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active " href="#section_2">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active " href="#section_3">Players</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active " href="#section_4">Schedule</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active " href="#section_5">Pricing</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active " href="#section_6">Contact</a>
          </li>
          <li class="nav-item">
            <button class="btn">Buy Ticket</button>
          </li>
          
   
        </ul>
      </div>
   </nav>
</template>

<style scoped>

.navbar{
    background: transparent;
  z-index: 9;
  position: fixed;
  width: 100%;
  top: 0;
  left: 0;
}
#brand{
    margin-left: 10%;
    color: #EE5007;
    font-weight: 800;
    font-size: 30px;
}
#navbarNav{
    margin-right: 10%;
    

  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}
.nav-item{
    color: white;
    margin-left: 20px;
}
.nav-item a:hover{
color: #EE5007;

}
button {
    width: 120px;
    background-color:  #EE5007;
    color:white;
    border-radius: 25px;
}
button:hover{
    background-color: #c01f27;
    color: white;
}
</style>

