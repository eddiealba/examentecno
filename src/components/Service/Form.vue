<template>
  <section class="contact-area pb-90">
    <div class="container">
      <div class="row">
        <div class="col-lg-8">
          <div class="contact-box">
            <form action="#">
              <h3 class="title">
                Servicios <br />
                Complete la forma.
              </h3>
              <select name="categoria" id="cat">
                <option value="Inmueble">Inmueble</option>
                <option value="Servicio">Servicio</option>
                <option value="Compra Venta">Compra Venta</option>
              </select>
              <div class="row">
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="text" placeholder="Nombre Completo" />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="text" placeholder="Domicilio" />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="email" placeholder="Direccion Email" />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="email" placeholder="Telefono fijo" />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="text" placeholder="Telefono Celular" />
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                    <input type="text" placeholder="Carnet de Identidad / NIT" />
                  </div>
                </div>

                <div class="col-md-6">
                  <div class="input-box">
                  <input type="text" id="inputNumero" maxlength="19" autocomplete="off" placeholder="Numero de Tarjeta">
                  </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                  <input type="text" id="inputNombre" maxlength="19" autocomplete="off" placeholder="Nombre de Tarjeta">
                  </div>
                </div>
                <div class="col-md-6">
                  <label for="selectMes">Expiracion</label>
                    <div class="flexbox">
                      <div class="grupo-select">
                        <select name="mes" id="selectMes">
                          <option disabled selected>Mes</option>
                        </select>
                      
                        <select name="year" id="selectYear">
                          <option disabled selected>Año</option>
                        </select>
                        </div>
                </div>
                <div class="col-md-6">
                  <div class="input-box">
                  <input type="text" id="inputCCV" maxlength="3" placeholder="CCV">
                </div>      
                </div>
                
                </div>
                <div class="col-lg-12">
                  <div class="input-box">
                    <textarea
                      name="#"
                      id="#"
                      cols="30"
                      rows="10"
                      placeholder="Descripcion de la publicidad"
                    ></textarea>
                    <button class="main-btn">Enviar</button>
                  </div>
                </div>
              </div>
            </form>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="contact-sidebar">
            <FromCount />
            <signup-style-one />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import FromCount from "../Utility/FollowCount/index";
import SignupStyleOne from "../Utility/Signup/SignupStyleOne.vue";
export default {
  components: { FromCount, SignupStyleOne },
};
</script>

<style></style>
