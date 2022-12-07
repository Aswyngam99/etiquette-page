<template>
     <div>
        <Navigation/>
      <v-card tile class="back" height="200">
      </v-card>
   <!-- infos -->
          <v-card tile flat class="mx-6 my-6">
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">1. Objet</h2>
                <p>Cette procédure décrit les étapes à suivre pour effectuer une analyse étiquette.</p>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">2. Domaine d'application</h2>
                <p>Cette procédure s’applique au laboratoire Henkel Reghaia.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">3. Document de Référence</h2>
                 <v-list-item two-line>
                    <v-list-item-content>
                        <v-list-item-title><strong>- ISO 9000 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Principes essentiels et vocabulaire.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9001 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Exigences.</v-list-item-subtitle>
                        <v-list-item-title><strong>- ISO 9002 :</strong></v-list-item-title>
                        <v-list-item-subtitle>Systèmes de management de la qualité — Lignes directrices pour l’application de l’ISO 9001:2015.</v-list-item-subtitle>
                    </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
            <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">4. Définitions et Abréviations</h2>
                <p>Non indiquées.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
                <h2 class="titre">5. Responsabilités et Autorités</h2>
                <p>Le technicien contrôle qualité est responsable sur l’analyse.</p>
                </v-card-text>
            </v-card>
             <v-card class="mx-2 my-2 px-2 py-2 confirm-card">
                <v-card-text>
            <h2 class="titre">6. Processus</h2>
                <v-list-item>
                <v-list-item-content>
                    <v-list-item-title>- Effectuer une série d’essai de 150cm.</v-list-item-title>
                    <v-list-item-title>- Effectuer les Dimension à l’aide d’une règle.</v-list-item-title>
                    <v-list-item-title>- Diamètre à l’aide d’un Pied à coulisse électronique.</v-list-item-title>
                    <v-list-item-title>- Prendre note de différents points selon la spécification.</v-list-item-title>
                    <v-list-item-title>- Enregistrer les données.</v-list-item-title>
                </v-list-item-content>
                </v-list-item>
                </v-card-text>
            </v-card>
           </v-card>
             <!-- Footer -->
            <v-footer flat bottom padless>
                <v-col><strong>PR SHEQ VR A.5-01– Procédure de Veille Réglementaire</strong> <br> <div class="primary--text"> Propriété exclusive de HENKEL Algérie Unité de Production Réghaia. <br> Toute reproduction intégrale ou partielle ainsi que son utilisation par, ou la communication à, des tiers, sans accord préalable écrit de l’auteur est illicite.</div> Le R-SMI est responsable de la gestion et l’application de cette procédure.</v-col>
            </v-footer>
    </div>
</template>

<script>
  export default {
    name: 'HelloWorld',

    data: () => ({

    }),
  }
</script>
<style scoped>
.confirm-card {
  overflow: hidden;
}
.titre{
    color: #ff0011;
}
.back{
    background: url('../../public/labo3.jpg');
}
</style>