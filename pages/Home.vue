<template>
   <div>
      <section id="hero">
      <div class="container text-center">
         <div class="row">
            <div class="col-12 text-center">
               <h5>An item is about to expire</h5>
            </div>
         </div>
         <div class="row d-flex justify-content-center mt-3">
            <div class="col-md-4 text-center image-hero position-relative">
               <img src="~/assets/img/red potatoes.png" alt="Red Potatoes">

               <span class="d-block position-absolute bottom-25 bg-danger start-50 translate-middle-x p-1 label">
                  2 days
               </span>
            </div>
         </div>
         <button class="button-primary mt-5">View</button>
      </div>
   </section>

   <section id="recipe">
      <div class="container-fluid p-4 mt-5">
         <div class="row">
            <div class="col-12 text-center">
               <h4 class="mt-5">Recipes with My Food</h4>
            </div>
         </div>

         <div class="row d-flex mt-3">
            <div class="col-md-4">
               <div class="card-item">
                  <div class="card-image">
                     <img src="~/assets/img/red potatoes.png" alt="">
                  </div>
                  <div class="card-body ps-3 mt-2">
                     <h5 class="title">Eggplant Parmesan</h5>
                     <p class="description text-muted">Lorem ipsum dolor</p>
                  </div>
               </div>
            </div>
            <div class="col-md-4">
               <div class="card-item">
                  <div class="card-image">
                     <img src="~/assets/img/red potatoes.png" alt="">
                  </div>
                  <div class="card-body ps-3 mt-2">
                     <h5 class="title">Eggplant Parmesan</h5>
                     <p class="description text-muted">Lorem ipsum dolor</p>
                  </div>
               </div>
            </div>
            <div class="col-md-4">
               <div class="card-item">
                  <div class="card-image">
                     <img src="~/assets/img/red potatoes.png" alt="">
                  </div>
                  <div class="card-body ps-3 mt-2">
                     <h5 class="title">Eggplant Parmesan</h5>
                     <p class="description text-muted">Lorem ipsum dolor</p>
                  </div>
               </div>
            </div>
         </div>

         <div class="row mt-5 mb-3">
            <div class="col-md-12 text-center">
               <button class="button-primary">View all recipes</button>
            </div>
         </div>
      </div>
   </section>
   </div>
</template>