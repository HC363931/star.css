# star.css
#banner {
    position: relative;
    width: 1000px;
    height: 600px;
    margin: 8px; 
  }
  #canvas {
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    width: 100%;
    height: 100%;
    background-color: transparent;
  }


  #fname{
    border: none;
    background-color: transparent;
    resize: none;
    outline: none;
}

#fdob{
  border: none;
  background-color: transparent;
  resize: none;
  outline: none;
}






.card {

  background: linear-gradient(45deg, rgba(0,1,19,1) 0%,rgba(1,10,53,1) 15%,rgba(1,13,61,1) 60%,rgba(0,1,19,1) 100%); 
  border-radius: 4px;
  height: 85vh; 
  width: 80vw;  
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.16), 0 3px 6px rgba(0, 0, 0, 0.23); 
  text-align: center;
  display: flex; 
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 1em;
  overflow: hidden;
}

@media only screen and (min-width: 1000px) {
  .card {
    flex-direction: row-reverse;
  }
  .card img.birthday {
    width: 100%;
    max-width: 50vw;
    max-height: unset;
  }
}

@media only screen and (max-height: 640px) {
  .card {
    flex-direction: row-reverse;
  }
  .card img.birthday {
    width: 100%;
    max-width: 50vw;
    max-height: unset;
  }
}

img.birthday {
  max-height: 40vh;
}

.text {
  padding: 1em;
}

.muted {
  opacity: 0.8;
}

.space {
  height: 100px;
}
