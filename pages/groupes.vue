<template>
  <div>
    <section class="jumbotron text-center">
      <div class="container">
        <h1>Groupes de travail</h1>
        <p class="lead text-muted">
          La conception et la fabrication des dispositifs suivants sont des
          priorités sanitaires. Les groupes de travail ont pour objectif de
          mettre au point et valider des solutions standard pour toutes nos
          équipes afin de les produire en grande quantité.
        </p>
      </div>
    </section>

    <table class="table table-striped">
      <thead class="thead">
        <tr>
          <th scope="col">Groupe</th>
          <th scope="col">Responsable</th>
          <th scope="col">Mail</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <th scope="row">
            <a href="/projet_masque">Masque</a>
          </th>
          <td>Landrain</td>
          <td><a href="mailto:thomas@jogl.io">thomas@jogl.io</a></td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_poignee">Poignée</a>
          </th>
          <td>Adam</td>
          <td>
            <a href="mailto:jeremy.adam@bone3d.fr">jeremy.adam@bone3d.fr</a>
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_pousse_seringue">Pousse-seringue</a>
          </th>
          <td>Dahmani</td>
          <td>
            <a href="mailto:souhayl.dahmani@gmail.com"
              >souhayl.dahmani@gmail.com</a
            >
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_intubation">Intubation</a>
          </th>
          <td>de Montblanc / Dallard</td>
          <td>
            <a href="mailto:jacques.de-montblanc@aphp.fr">jacques.de-montblanc@aphp.fr</a>
            <a href="mailto:jeremy.dallard@ensta-paristech.fr">jeremy.dallard@ensta-paristech.fr</a>
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_respirateur">Respirateur</a>
          </th>
          <td>Monteil</td>
          <td>
            <a href="mailto:cecile.monteil@aphp.fr">cecile.monteil@aphp.fr</a>
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_bouclier_nasal">Bouclier nasal</a>
          </th>
          <td>Kogane</td>
          <td>
            <a href="mailto:nicolas.kogane@gmail.com"
              >nicolas.kogane@gmail.com</a
            >
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_visiere">Visière</a>
          </th>
          <td>Attal</td>
          <td>
            <a href="mailto:jean-pierre.attal@parisdescartes.fr"
              >jean-pierre.attal@parisdescartes.fr</a
            >
          </td>
        </tr>
        <tr>
          <th scope="row">
            <a href="/projet_masque_plongee">Masque Plongée</a>
          </th>
          <td>Bénichou / Kétoff</td>
          <td>
            <a href="mailto:lbenichou@hpsj.fr">lbenichou@hpsj.fr</a>
            <a href="mailto:sketoff@hpsj.fr">sketoff@hpsj.fr</a>
          </td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>
