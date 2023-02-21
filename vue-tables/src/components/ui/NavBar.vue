<template>
    <div>
        <nav className="navbar">
      <ul className="nav-links">
        <div className="menu">
          <li><a href="/">Time</a></li>
          <li><a href="/second">Date</a></li>
          <li><a href="/table">Table</a></li>
        </div>
      </ul>
    </nav>
    </div>
    </template>
    
    <script>
    
    </script>
    
    <style>
    .navbar {
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 7px;
    background-color: rgb(0, 133, 133);
    color: #fff;
    }
    
    .nav-links a {
        color: #fff;
    }

    .menu {
        display: flex;
        gap: 1em;
        font-size: 18px;
        }   

    .menu li:hover {
        background-color: #4c9e9e;
        border-radius: 5px;
        transition: 0.3s ease;
        }
    </style>