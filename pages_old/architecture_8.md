# The Architecture

Shallue and Vanderburg (2017)

<div class="grid grid-cols-3 justify-center justify-items-center items-start">
<div class="flex flex-col justify-center items-center">
  <img src="/images/ajaa9e09f7_hr.jpg" class="max-h-100 p-2 shadow-xl -mb-5" />

</div>
<div class="list col-span-2">
<div>

* Both inputs are being convoluted seperately at first
* Global view uses five sets of convolutions while local view uses two sets

</div>
<div class="not-active">

* ConvX-Y denotes convolutional layers with a kernel size of X and Y filters
* MaxpoolX-Y denots max pooling layers with a range of X and a stride of Y
</div>
</div>

</div>

<style>
  .not-active {
    opacity: 20%;
  }
  .list li{
    margin-bottom: 1.8rem !important;
  }
</style>