# typesetting

# * {
    box-sizing: border-box;
    outline: none;
  }
  
  body {
    margin: 0 auto;
    min-width: 1000px;
    max-width: 1400px;
  }
  
  /* Layout */
  
  
  section {
    float: left;
    width: 50%;
  }
  
  aside {
    float: left;
    width: 30%;
  }
  
  nav {
    float: left;
    width: 20%;
  }
  
  footer {
    clear: both;
  }
  
  header, section, aside, nav, footer {
    padding: 20px;
  }
  
  /* header and footer */
  
  header, footer {
    border-top: 5px solid #a66;
    border-bottom: 5px solid #a66;
  }

  h1 {
    font-family: "Sofia", sans-serif;
    text-align: center;
  }
  li {
    font-family: Arial, Helvetica, sans-serif;
  }

  a {
    color:#a66;
  }

  h2 {
    font-family: "Roboto", sans-serif;
  }

  p {
    font-size:16px;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 20px;
    text-indent: 1.25rem;
  }

  a[href^="https"]:after{
    content: "";
    display: inline-block;
    width: 12px;
    height: 12px;
    background-image: url('external-link.png');
    background-size: contain;
    background-repeat: no-repeat;
    margin-left: 5px;
  }

  nav li {
    font-size: 30px;
    background-color: rgb(255, 255, 255);
    list-style-type: none;
    margin: 0;
    padding: 10px;
    list-style-type: none;
    overflow: hidden;
    border-color: #a66;
    margin: 10px;
    border-style: ridge;
  }

  a:hover {
    color: rgb(69, 120, 179);
    text-decoration: none;
  }

  a:focus{
    color:rgb(48, 179, 189);
    text-decoration: none;
  }

  a:visited {
    color: rgb(32, 145, 83);
  } 

  a:active {
    color: #945b5b;
    background-color: #a66;
    padding: 2px 5px;
    border-radius: 3px;
    transform: scale(0.98);
}
  
  nav a{
    color: black;
    text-decoration: none;
    display: block;
    text-align: center;
  }

  nav a:hover {
    background-color:rgb(252, 213, 213);
#  }
 
