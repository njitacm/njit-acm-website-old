<template>
<div>
 <h1 class="m-2 text-center">SIG</h1>
    <CurrSig sigTitle="Sig Playas but Better Faster Harder Stronger" leader="Ethan" leaderTime="All the time" sigDesc="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum." logo="https://cdn.bootstrapstudio.io/placeholders/1400x800.png" />
    <CurrSig sigTitle="Sig Playas but Better Faster Harder Stronger" leader="Ethan" leaderTime="All the time" sigDesc="Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum." logo="https://cdn.bootstrapstudio.io/placeholders/1400x800.png" />
    <hr>
    <b-container>
      <b-row>
        <b-col lg="4" sm="6"><LegacySig leader="Ethan" year="Fall 2099" sigName="Sig Playas"/></b-col>
        <b-col lg="4" sm="6"><LegacySig leader="Ethan" year="Fall 2099" sigName="Sig Playas"/></b-col>
        <b-col lg="4" sm="6"><LegacySig leader="Ethan" year="Fall 2099" sigName="Sig Playas"/></b-col>
        <b-col lg="4" sm="6"><LegacySig leader="Ethan" year="Fall 2099" sigName="Sig Playas"/></b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

import LegacySig from '../components/LegacySig.vue';
import CurrSig from '../components/CurrSig';

export default {
  components: {
    LegacySig,
    CurrSig
  },

  name: 'SIGS'
}
</script>

<style>
  .card{
      background-color: #d1d2d4 !important;
      box-shadow: 0px 0px 15px rgb(185, 184, 184);
  }
</style>
