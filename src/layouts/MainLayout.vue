<template>
  <q-layout view="hHh lpR fFf">

    <q-page-container class="q-pa-lg bg-secondary">

      <div class="q-pa-md bg-white container">
        <div class="row ">
          <div class="col">
            <div class="row justify-center q-pt-lg">

              
                <div class="row">
                  <div class="circle-1">
                    <div class="circle-2"></div>
                  </div>
                  <p class="logo q-pl-sm">Proom</p>
                </div>
              

              <div class="links q-gutter-x-sm">
                <a class="q-ml-xl">Courses</a>
                <a>Features</a>
                <a >Support</a>
              </div>

              <div class="q-gutter-x-sm q-ml-xl mobile-hide">
                <q-btn dense round flat icon="email">
                  <q-badge color="red" floating transparent>
                    5
                  </q-badge>
                </q-btn>
                <q-avatar  size="30px">
                  <img src="https://cdn.quasar.dev/img/avatar.png">
                </q-avatar>
              </div>
            </div>
            <div >
              <div class="row header q-mt-xl text-center">          
                  <h4>
                    Study different areas of web design easily in 3 steps:
                  </h4>
              
              </div>

              <div class="row description justify-center">
                <div>
                  <p><span class="q-mr-sm">01.</span>Visit our website </p>
                  <p><span class="q-mr-sm">02.</span>Sign Up</p>
                  <p><span class="q-mr-sm">03.</span>Find the Course You want</p>
                </div>
              </div>

              <div class="row justify-center">
                <q-btn rounded
                       class="q-px-xl q-py-xs q-mt-lg"
                       size=""
                       color="primary"
                       label="Sign in" />

              </div>

            </div>
          </div>
          <div class="mobile-hide	col q-pa-md" >
            <div class="background relative-position">
              <div class="row justify-center">
                  <q-img src="../assets/stationaries.svg" class="absolute-center img"/>
              
              </div>
              <div class="row absolute-bottom justify-center q-mb-md">
                <div class="control-1 q-mr-sm"></div>
                <div class="control-2"></div>
                <div class="control-3 q-ml-sm"></div>
              </div>
            </div>

            
          </div>
        </div>
      </div>
    </q-page-container>

  </q-layout>
</template>

<script>

  export default {
    data() {
      return {
        slide: 1

      }
    }
    }
</script>
