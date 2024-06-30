# High Resolution *Cross Correlation* Retrieval

Fisher et al. (2020)

<div class="grid grid-cols-3 justify-center justify-items-center items-center">
<div class="col-span-2"> 
  <img src="/images/cc_template.png" class="max-h-85 shadow-xl p-1 -mt-5" />
</div>

<div class="ml-5 list col-span-1">

* We transform these noisy spectra into cross correlation templates
* 64 templates in total with 40 $v_r$ values each
* Each template contains the CC for different parameters
* This can then be used to train a Random Forrest

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
    margin-bottom: 1.8rem !important;
  }
</style>

<!--
The parameters we search for here are:
* Temperature
* Metallicity
-->
