<template>
  <div>
    <div>
      <div class="pricing-header px-3 py-3 pt-md-5 pb-md-4 mx-auto text-center">
        <section class="lead">
          <img src="/landing/landing-logo.png" style="width: 80%" />
          <h4 style="color: #0646ad;">
            CONCEVOIR - VALIDER - FABRIQUER - DISTRIBUER - COMBATTRE LE VIRUS
          </h4>
          <br />
          Plateforme interne d'impression haut-débit pour répondre aux besoins
          sanitaires urgents des soignants
          <br />
          Fédération des initiatives de conception et d’impression 3D pour lutter
          contre le COVID-19 en Île-de-France
        </section>
      </div>
    </div>
    <div class="container">
      <div class="card-deck mb-3 text-center">
        <div class="card mb-6 shadow-sm">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Soignant</h4>
          </div>
          <nuxt-link to="/soignant">
            <img src="landing/landing-caducee.png" class="card-img-top" />
          </nuxt-link>
          <div class="card-footer">
            <nuxt-link to="/soignant">
              <button type="button" class="btn btn-lg btn-block btn-primary">
                J'ai besoin d'équipement
              </button>
            </nuxt-link>
          </div>
        </div>

        <div class="card mb-6 shadow-sm">
          <div class="card-header">
            <h4 class="my-0 font-weight-normal">Ingénieur / Fabricant</h4>
          </div>
          <nuxt-link to="/soignant">
            <img src="/landing/landing-valve.png" class="card-img-top" />
          </nuxt-link>
          <div class="card-footer">
            <nuxt-link to="/soignant">
              <button type="button" class="btn btn-lg btn-block btn-primary">
                Venez nous aider
              </button>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>

    <br />
    <hr />
    <div class="container">
      <div class="row">
        <div class="col-sm-12 text-center">
          Avec le généreux soutien de
          <br />
          <img src="/logos/logo-Kering.jpg" style="height: 150px" />
          <br />
        </div>
      </div>
      <div class="row">
        <div class="col-sm-12 text-center">
          <br />
          <img src="/logos/nuage-logos.png" style="width: 100%" />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  
})
</script>
