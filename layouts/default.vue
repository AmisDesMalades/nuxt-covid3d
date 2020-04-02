<template>
  <div class="nuxt-body">
    <b-navbar class="bg-light">
      <b-container>
        <b-navbar-brand href="/">3D COVID</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="/conseil">
              Conseil Scientifique
            </b-nav-item>
            <b-nav-item to="/groupes">
              Groupes de travail
            </b-nav-item>
            <b-nav-item-dropdown text="Projets">
              <b-dropdown-item to="/projet_visiere">
                Visière
              </b-dropdown-item>
              <b-dropdown-item to="/projet_poignee">
                Poignée
              </b-dropdown-item>
              <b-dropdown-item to="/projet_masque">
                Masque
              </b-dropdown-item>
              <b-dropdown-item to="/projet_pousse_seringue">
                Pousse-seringue
              </b-dropdown-item>
              <b-dropdown-item to="/projet_intubation">
                Intubation
              </b-dropdown-item>
              <b-dropdown-item to="/projet_masque_plongee">
                Masque de plongée
              </b-dropdown-item>
              <b-dropdown-item to="/projet_respirateur">
                Respirateur
              </b-dropdown-item>
              <b-dropdown-item to="/projet_bouclier_nasal">
                Bouclier Nasal
              </b-dropdown-item>
            </b-nav-item-dropdown>
            <b-nav-item to="/infrastructure">
              Infrastructure
            </b-nav-item>
            <b-nav-item to="/announcements">
              Nouvelles
            </b-nav-item>
            <b-nav-item to="/contact">
              Contact
            </b-nav-item>
            <b-nav-item to="/admin">
              Admin
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-container>
    </b-navbar>
    <b-container>
      <nuxt />
    </b-container>
    <footer class="footer text-muted bg-light d-none d-sm-block">
      <b-container>
        <ul class="list-inline mb-0 float-right">
          <li class="list-inline-item mr-3">
            <a href="mailto:philippe@cochin.fr?subject=Site%203D%20COVID">
              Contact technique
            </a>
          </li>
          <li class="list-inline-item mr-3">
            <nuxt-link to="/terms">
              CGU
            </nuxt-link>
          </li>
          <li class="list-inline-item mr-3">
            <nuxt-link to="/privacy_path">
              Politique de confidentialité
            </nuxt-link>
          </li>
        </ul>
      </b-container>
    </footer>
  </div>
</template>
