<template>
   
<div class="tm-header uk-visible@s" uk-header="">


        <div uk-sticky="" media="768" show-on-up="" animation="uk-animation-slide-top" cls-active="uk-navbar-sticky" sel-target=".uk-navbar-container">
        <div class="uk-navbar-container fondo">
        <div class="uk-container uk-container-expand fondo">
        <nav class="uk-navbar" uk-navbar="{&quot;align&quot;:&quot;left&quot;,&quot;boundary&quot;:&quot;!.uk-navbar-container&quot;}">
        <div class="uk-navbar-left">
                   
                   <a href="/" class="uk-navbar-item uk-logo">
                      <img src="https://jaimeduenasmalo.com/templates/yootheme/cache/logo-04-c8946175.webp" srcset="https://jaimeduenasmalo.com/templates/yootheme/cache/logo-04-c8946175.webp" sizes="(min-width: 181px) 181px" data-width="604" data-height="209" alt="jdm."></a>                      
                    </div>
                    
                    
        <div class="uk-navbar-right">
            <ul class="uk-navbar-nav letter uk-text-bold uk-text-large">
	            <li class= "uk-padding-small"><nuxt-link to = "perfil">Perfil</nuxt-link></li>
                <li class= "uk-padding-small"><nuxt-link to = "obras">Obras</nuxt-link></li>
            </ul>
        </div>
                    
        </nav>
    </div>

    </div>
  </div>
</div>
    
</template>



<script>
export default {

}
</script>

<style>
    header {
        background: rgb(1, 204, 79);
        display: grid;
        grid-template-columns: repeat(1,auto);

    }

    .logo {
        padding: 1em 2em;
        display: block;
        text-transform: uppercase;
        text-decoration: none;
        font-weight: bold;
        color: white;
        font-size: .9em;

    }

    nav {
        justify-self: right;
    }

    ul {
        list-style-type: none;
    }

    .letter {
        font-size: 50em;
    }

    .fondo {
        background: rgb(255, 255, 255);
    }
</style>
