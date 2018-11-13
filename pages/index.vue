<template>
  <section class="uk-padding-remove">
 
       <div class = "" uk-slideshow="min-height: 250; max-height: 1000; animation: fade; autoplay: true autoplay-interval: 10">
            <div class="uk-position-relative uk-light">

                <ul class="uk-slideshow-items">
                    <li>
                        <img src="https://jaimeduenasmalo.com/images/fotografias/portada2.jpg" alt="" uk-cover>
                     </li>
                    <li>
                        <img src="https://jaimeduenasmalo.com/images/fotografias/Home1.jpg" alt="" uk-cover>
                    </li>
                     <li>
                        <img src="https://jaimeduenasmalo.com/images/fotografias/Home3.jpg" alt="" uk-cover>
                    </li>
                    <li>
                        <img src="https://jaimeduenasmalo.com/images/fotografias/Home2.jpg" alt="" uk-cover>
                    </li>
                </ul>           

                    <a class="uk-slidenav-large uk-position-center-left uk-position-small" href="#" uk-slidenav-previous uk-slideshow-item="previous"></a>
                    <a class="uk-slidenav-large uk-position-center-right uk-position-small" href="#" uk-slidenav-next uk-slideshow-item="next"></a>

                <div class="uk-position-bottom-center uk-position-small">
                    <ul class="uk-dotnav">
                        <li uk-slideshow-item="0"><a href="#">Item 1</a></li>
                        <li uk-slideshow-item="1"><a href="#">Item 2</a></li>
                        <li uk-slideshow-item="2"><a href="#">Item 3</a></li>
                        <li uk-slideshow-item="3"><a href="#">Item 4</a></li>
                    </ul>
                </div>

            </div>
        </div>

        <footer class= "fondofoot">
            <div class="uk-section-secondary uk-section fondofoot">
                <div class="uk-container uk-container-small uk-margin-small">
                    <div class="uk-grid-large" uk-grid="">
                        <div class="uk-width-expand@m">
                        <div><form id="contact-form" method="post" action="../extras_jdm/mailer.php" class="uk-grid-small uk-align-center" uk-grid="">

                            <div class="uk-width-1-1">
                                <div class="uk-margin">
                                    <div class="uk-inline">
                                        <span class="uk-form-icon" uk-icon="icon: user"></span>
                                        <input id="nombre-contacto" name="nombre-contacto" class="uk-input uk-form-success uk-form-width-large" type="text" placeholder="Nombre y Apellido">
                                    </div>
                                </div>
                            </div>

                            <div class="uk-width-1-1">
                                <div class="uk-margin">
                                    <div class="uk-inline">
                                        <span class="uk-form-icon" uk-icon="icon: mail"></span>
                                        <input id="email-contacto" name="email-contacto" class="uk-input uk-form-success uk-form-width-large" type="text" placeholder="Correo Electrónico">
                                    </div>
                                </div>
                            </div>

                            <div class="uk-width-1-1">
                                <div class="uk-margin">
                                    <div class="uk-inline">
                                        <span class="uk-form-icon" uk-icon="icon: phone"></span>
                                        <input id="telefono-contacto" name="telefono-contacto" class="uk-input uk-form-success uk-form-width-large" type="text" placeholder="Teléfono de contacto">
                                    </div>
                                </div> 
                            </div>

                            <div class="uk-width-1-1">
                                <div class="uk-margin">
                                    <div class="uk-inline">
                                        <span class="uk-form-icon" uk-icon="icon: location"></span>
                                        <input id="ciudad-contacto" name="ciudad-contacto" class="uk-input uk-form-success uk-form-width-large" type="text" placeholder="Ciudad">
                                    </div>
                                </div>
                            </div>

                            <div class="uk-width-1-1">
                                <div class="uk-margin">
                                    <textarea id="mensaje-contacto" name="mensaje-contacto" class="uk-textarea uk-form-success uk-form-width-large" rows="5" placeholder="¿Cómo podemos ayudarte?"></textarea>
                                </div>
                            </div>

                            <div class="uk-width-1-1">
                                <div class="uk-align-center">
                                    <div class="g-recaptcha" data-sitekey="6LfnpXQUAAAAAO4CTKiNj_IvFaz5V29vCxy6DQ_t">
                                    </div> <br>
             
                                    <div id="output-contacto">
                                        <ul>
                                        </ul>
                                    </div>  
                                    <div><button id="submitButton" class="uk-button uk-button-secondary" type="submit">ENVIAR</button></div>
                                </div>
                            </div>
                        </form></div>
                        </div>

                        
                        <div class="uk-width-expand@m">
                            <h5 class="uk-text-center uk-h5">
                                Contacto    
                            </h5>

                        <ul class="uk-margin-medium uk-width-medium uk-margin-auto uk-list">

                            <li class="el-item">
                                <div class="uk-grid-small uk-child-width-expand uk-flex-nowrap uk-flex-middle" uk-grid="">
                                    <div class="uk-width-auto">
                                        <span uk-icon="icon: location" class="el-image"></span>        
                                    </div>
                                    <div>
                                        <div class="el-content">
                                        Calle Inés Gangotena S/N y Vía Amaguaña. Sangolquí - Ecuador 
                                        </div>
                                    </div>
                                </div>
                            </li>
                            
                            <li class="el-item">
                                <div class="uk-grid-small uk-child-width-expand uk-flex-nowrap uk-flex-middle" uk-grid="">
                                    <div class="uk-width-auto">
                                        <span uk-icon="icon: receiver" class="el-image"></span>
                                    </div>
                                    <div>
                                        <div class="el-content">
                                        +593 02 2197128
                                        </div>
                                    </div>
                                </div>
                            </li>

                            <li class="el-item">
                                <div class="uk-grid-small uk-child-width-expand uk-flex-nowrap uk-flex-middle" uk-grid="">
                                    <div class="uk-width-auto">
                                        <span uk-icon="icon: phone" class="el-image"></span>       
                                    </div>
                                    <div>
                                        <div class="el-content">
                                            +593 998041619            
                                        </div>
                                    </div>
                                </div>
                            </li>

                            <li class="el-item">
                                <div class="uk-grid-small uk-child-width-expand uk-flex-nowrap uk-flex-middle" uk-grid="">
                                    <div class="uk-width-auto">
                                        <span uk-icon="icon: mail" class="el-image"></span>        
                                    </div>
                                    <div>
                                        <div class="el-content">
                                            <a href="https://www.nidointeractive.com/" target="_blank">jaimeduenasmalo@gmail.com</a>.
                                        </div>
                                    </div>
                                </div>
                            </li>
    
                        </ul>
                            <div><div class="uk-margin-large"></div></div>
                            <div class="uk-margin-xlarge">
                            <p>© 2018 Jaime Dueñas Malo. Todos los derechos reservados. Sitio web desarrollado por <a href="https://www.nidointeractive.com/" target="_blank">Nido Interactive</a>.</p></div>

                        </div>
                    </div>
                </div>
                    <div class="uk-grid-margin" uk-grid="">
                        <div class="uk-width-1-1@m">    
                        </div>
                    </div>
            </div>
        </footer>
    </section>
</template>

<script>

export default {
 head () {
          return {
                title: 'Inicio',
                meta: [
                    { Name: 'description', content: 'This is a description here Home'},
                    { Name: 'Keywords', content: 'About Nuxt, Nuxt info'},
                ]
                }

            }
}
</script>

<style>

.fondofoot {
    background: rgb(82, 82, 82);
}
</style>

