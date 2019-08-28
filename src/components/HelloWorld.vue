<template>
  <div class="container">
    <h1>Todo List</h1>
    <br>
    <div class="row">
      <div class="col-md-6 offset-md-3">
        <form>
          <div class="form-group">
            <label for="exampleFormControlInput1">Titulo</label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Titulo de la Tarea">
          </div>
          <div class="form-group">
            <label for="exampleFormControlInput1">Descripción</label>
            <input type="text" class="form-control" id="exampleFormControlInput1" placeholder="Descripción de la tarea">
          </div>
          <div class="form-group">
            <label for="exampleFormControlSelect1">Importancia</label>
            <select class="form-control" id="exampleFormControlSelect1">
              <option>1</option>
              <option>2</option>
              <option>3</option>
              <option>4</option>
              <option>5</option>
            </select>
          </div>
          <button type="submit" class="btn btn-danger">Crear</button>
        </form>
      </div>
    </div>
    <br>
    <div class="row">
      <div class="col-md-12 flex">
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Titulo tarea</h5>
            <h6 class="card-subtitle mb-2 text-muted">Importancia</h6>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="card-link">Terminada</a>
            <a href="#" class="card-link">Borra</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

h1 {
  font-family: 'Open Sans', sans-serif;
  font-size: 50px;
}
.flex{
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}
.card{
  margin: 20px 0;
}
a{
  color: #E24656;
}
</style>
