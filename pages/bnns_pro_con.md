# What are BNNs?

Jospin et al. (2022)

<div class="grid grid-cols-2 justify-center justify-items-center items-center">
<div>  
  <img src="/images/bnn_schem.png" class="max-h-90 -mt-5 shadow-xl" />
</div>
<div class="ml-5 list">

* They are able to give you uncertanties in a more statistical sense
* At least you are aware of your prior (while you might forget about it in different approaches)
* This might be useful in cases with limited training data

<div class="opacity-20">

* Quite complex models
* Still expensive to run due to MCMC or similar calculations
</div>

</div>
</div>

<style>
  a {
    border-style: none !important;
  }

  a:hover {
    border-style: none !important;
  }

  .list li{
    margin-bottom: 1.3rem !important;
  }
</style>

<!--
Loss is negative log-likelihood
-->
