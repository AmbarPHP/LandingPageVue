<template>
  <!-- feature -->
  <section id="Distribution">
    <div class="container">
      <div class="row">
        <div class="col-xs-12 col-md-6 col-lg-6 px-0">
          <h2 class="text-uppercase">Procesos de distribución</h2>
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-md-6 px-0">
          <ul>
            <p>
              Pasos de distribución y venta
              Almacén.
              Recepción de suministros.
              Aprovisionamiento y compras.
              Transporte externo.
              Transporte interno.
              Transporte interempresa.
              Distribución.
              Tratamiento y atención de los pedidos.
              Reciclaje de residuos y de los productos desechados por el cliente.
              Planificación de la producción.
              Control de producción.
              Información y comunicaciones.
              Control de calidad.
              Mantenimiento.
              Ventas.
            </p>
          </ul>
        </div>
        <div class="col-xs-12 col-md-6 px-0">
          <img class="img-responsive fix" src="../assets/images/infra.jpeg" alt="Feature img">
        </div>
      </div>
      <div class="row">
        <div class="col-xs-12 col-md-6 px-0">
          <img class="img-responsive fix" src="../assets/images/infra2.jpeg" alt="Feature img">
        </div>
        <div class="col-xs-12 col-md-6 px-0">
          <h2 class="text-uppercase">La distribución de productos industriales</h2>
          <p>
            Productores – usuarios industriales: este es el canal más usual para los productos de uso industrial ya que es mas corto y él más directo; utiliza representantes de ventas de la propia fabrica. Ejemplos : grandes fabricantes de metal, productores de bandas transportadoras, fabricantes de equipos para construcción y otros.
            Productores – distribuidores industriales – consumidores industriales: en este caso los distribuidores industriales realizan las mismas funciones de los mayoristas y en algunas ocasiones desempeñan las funciones de los mayoristas y en algunas ocasiones desempeñan las funciones de fuerza de ventas de los fabricantes.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Distribution",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
$color-resaltado: #00be00;
$color-complementario: #891e67;
$background-color: #fff;

#Distribution {
  background-color: $color-complementario; //#42b983;
  height: 100%;
  width: 100%;
  margin-top: 15vh;
  // top: 0;
  // left: 0;
  //opacity: 0.3;//opacidad para dar algo de diseño
  h2 {
    padding-top: 5vh;
    text-align: center;
    color: $color-resaltado;
  }
}
img.fix {
  height: 100%;
  width: 100%;
  align-content: center;
}
</style>
