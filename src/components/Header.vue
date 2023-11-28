<template>
  <div>
    <header class="header">
      <div class="header-user">
        <div class="content">
          Hi,Roshan
          <div class="icons">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              width="21%"
            >
              <path
                d="M14.857 17.082a23.848 23.848 0 005.454-1.31A8.967 8.967 0 0118 9.75v-.7V9A6 6 0 006 9v.75a8.967 8.967 0 01-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 01-5.714 0m5.714 0a3 3 0 11-5.714 0"
              />
            </svg>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              width="21%"
            >
              <path d="M12 6v6h4.5m4.5 0a9 9 0 11-18 0 9 9 0 0118 0z" />
            </svg>
            <div class="icons-foto">
              <img src="../assets/usuario.webp" alt="fotografia" />
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>


  <style scoped>
  * {
    margin: 0;
    padding: 0;
    
  }
  
  header {
    height: 100px;
    width: 100%;
    background: linear-gradient(to right, #0c80b9, #29a1dd);
    display: flex;
    
    
  }
  
  .header-user {
    border-radius: 2rem;
    border: solid #49b5eb;
    background-color: #49b5eb;
    display: flex;
    align-items: center;
    color: aliceblue;
    font-family: "Roboto", sans-serif;
    margin-left: 86%;
    width: 121%;
    margin-top: 30px;
    margin-bottom: 30px;
    
    

  }
  .content {
   display: flex;
   margin-left: 20px;
   align-items: center;
    
  }
  .icons {
    display: flex;
    align-items: center;
    
    
  }
  
  .icons-foto img {
    height: 35px;
    border-radius: 50%;
    margin-left: 20px;
    
  
  }
 
  
  </style>
