# base.css.read
Important css style


/*Important align content*/  https://www.youtube.com/watch?v=4YRG6cMAASI
.block{
  width: 200px;
  height: 200px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.html {
  display: none;
  display: block;
  display: inline;
  display: inline-block;
  display: flex;
  display: grid;
}
.block {
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}

.item {
  width: 200px;
  height: 200px;
  background: lightblue;
  animation: rotate 1s infinite;
}

@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

/*Position*/
.block {
  position: static; /*default*/
  position: relative;
  position: absolute;
  position: fixed;
  position: sticky;
}

/* If content go outside, no scroll */
.block {
  overflow: hidden;
}
.block {
  display: flex;
  flex-wrap: wrap; /* To move block in new line*/
}

