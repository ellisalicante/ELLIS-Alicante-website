---
title: XPrize on Pandemic Response
layout: page
lang: en
permalink: xprize
---

<link rel="stylesheet" href="{{ "/assets/css/xprize.css" | absolute_url }}">
<div class="container" id="xprize">
   <!-- VISTA  -->
   <div class="vista">
      <!-- MENU -->
      <div class="grupomenu">
         <ul>
            <a href="#" onclick="abrir_panel('pHome')" ><img class="icon" src="{{ "/assets/img/xprize/icono_1.png" | absolute_url }}" alt="" width="35px" height="40px"></a>
            <a href="#" onclick="abrir_panel('pOurVision')" ><img class="icon" src="{{ "/assets/img/xprize/icono_6.png" | absolute_url }}" alt="" width="35px" height="35px"></a>
            <a href="#" onclick="abrir_panel('pOurApproach')" ><img class="icon" src="{{ "/assets/img/xprize/icono_2.png" | absolute_url }}" alt="" width="35px" height="35px"></a>
            <a href="#" onclick="abrir_panel('pDataModelingTool')" ><img class="icon" src="{{ "/assets/img/xprize/icono_3.png" | absolute_url }}" alt="" width="35px" height="35px"></a>
            <a href="#" onclick="abrir_panel('pTheTeam')" ><img class="icon" src="{{ "/assets/img/xprize/icono_4.png" | absolute_url }}" alt="" width="35px" height="40px"></a>
            <a href="#" onclick="abrir_panel('pOtherInformation')" ><img class="icon" src="{{ "/assets/img/xprize/icono_5.png" | absolute_url }}" alt="" width="35px" height="35px"></a>
         </ul>
      </div>
      <!-- CONTENIDOS  -->
      <div class="grupocontenido">
        <!-- HOME -->
         <div class="page" id="pHome" style="display:block">
            <section class="card ficha">
               <div style="padding-top:120px">
                  <img class="center" src="{{ "/assets/img/xprize/logo_claro_c.png" | absolute_url }}" alt="" width="200px" height="200px">
               </div>
               <div style="padding:0px 60px">
                  <p class="center">“Research is to see what everybody else has seen, and to think what nobody else has thought.”</p>
                  <p class="center"><em>Albert Szent-Györgyi</em></p>
               </div>
            </section>
         </div>
         <!-- OUR VISION -->
         <div class="page" id="pOurVision"  style="display:none">
            <section class="card ficha">
               <h1>Our Vision</h1>
               <p class="center">"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."</p>
               <div class="card ov-overview">
                  <h2>Our Vision</h2>
                  <h3>Subtitulo</h3>
                  <p>Texto plano de lo que se quiere decir</p>
                  <br/>   
               </div>
            </section>
         </div>
         <!-- OUR APPROACH -->
         <div class="page" id="pOurApproach"  style="display:none">
            <section class="card ficha">
               <h1>Our Approach</h1>
               <p class="center" style="color:#fff">"Frase introductoria"</p>
               <!-- TARJETA 1 -->
               <div class="blog-card">
                  <div class="meta">
                     <div class="photo" style="background-image: url(https://storage.googleapis.com/chydlx/codepen/blog-cards/image-1.jpg)"></div>
                  </div>
                  <div class="description">
                     <h1>Patterns in reporting data</h1>
                     <h2>Este es un ejemplo de subtitulo</h2>
                     <p> Este es un ejemplo de una descripción de dos frases de lo que hace el elemento desarrollado en el contexto de la competición y que es presentado dentro de este espacio</p>
                     <p class="read-more">
                        <a href="#" onclick="abrir_panel('pPost1')">Read More</a>
                     </p>
                  </div>
               </div>
               <!-- TRAJETA 2 -->
               <div class="blog-card alt">
                  <div class="meta">
                     <div class="photo" style="background-image: url(https://storage.googleapis.com/chydlx/codepen/blog-cards/image-2.jpg)"></div>
                  </div>
                  <div class="description">
                     <h1>Segunda herramienta</h1>
                     <h2>Este es un ejemplo de subtitulo</h2>
                     <p> Este es un ejemplo de una descripción de dos frases de lo que hace el elemento desarrollado en el contexto de la competición y que es presentado dentro de este espacio</p>
                     <p class="read-more">
                        <a href="#" onclick="abrir_panel('pPost2')">Read More</a>
                     </p>
                  </div>
               </div>
            </section>
         </div>
         <!-- RESULTADOS -->
         <div class="page" id="pDataModelingTool"  style="display:none">
            <section class="card ficha">
               <h1>Data Modeling Tool</h1>
               <p class="center">"Aqui es donde en teoria voy a meter la herramienta de modelado."</p>
               <iframe frameborder="0" marginheight="0" marginwidth="0" title="Visualización de datos" allowtransparency="true" allowfullscreen="true" class="tableauViz" style="display: block; width: 100%; min-height: 2050px; max-height: 1964.7px; margin: 0px; padding: 0px; border: none; height: auto;" src="https://public.tableau.com/views/Covid19ImpactSurvey/Polticaspublicas?:embed=y&amp;:showVizHome=no&amp;:host_url=https%3A%2F%2Fpublic.tableau.com%2F&amp;:embed_code_version=3&amp;:tabs=yes&amp;:toolbar=yes&amp;:animate_transition=yes&amp;:display_static_image=no&amp;:display_spinner=no&amp;:display_overlay=yes&amp;:display_count=yes&amp;:loadOrderID=0"></iframe>
            </section>
         </div>
         <!-- EL EQUIPO -->
         <div class="page" id="pTheTeam"  style="display:none">
            <section class="card ficha fichaequipo">
               <h1>The Team</h1>
               <br/>
               <br/>
               <section>
                  <div class="container">
                     <div class="row flex-center sm-no-flex">
                        <div class="pull-right sm-no-float col-md-8">
                           <ul class="list-unstyled team-members">
                              <!-- single member row starts -->
                              <li class="clearfix">
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/dahe.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>David Hervas</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/dafu.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>David Fuente Herraiz</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/mire.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Miguel Rebollo</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/krpo.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Kristina Polotskaya</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                              </li>
                              <!-- /single member row ends -->
                              <!-- single member row starts -->
                              <li class="clearfix">
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/osga.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Òscar Garibo</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/aumu.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Aurora Mula Leal</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/rufe.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Rubén Femenía</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/alra.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Álex Rabasa</h3>
                                          <p>Leader</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/xaba.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Xavier Barber</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                              </li>
                              <!-- /single member row ends -->
                              <!-- single member row starts -->
                              <li class="clearfix">
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/nuol.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Nuria Oliver</h3>
                                          <p>Leader</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/fres.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Francisco Escolano</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/eles.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Elisa Espín</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/elpi.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Eloy Piñol Jimenez</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/magu.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Manuel G. Portolés</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                              </li>
                              <!-- /single member row ends -->
                              <!-- single member row starts -->
                              <li class="clearfix">
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/alco.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>J. Alberto Conejero</h3>
                                          <p>Leader</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/miga.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Miguel Angel Garcia-March</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/emsa.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Emilio Sansanor</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/milo.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Miguel Angel Lozano</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                              </li>
                              <!-- /single member row ends -->
                              <!-- single member row starts -->
                              <li class="clearfix">
                                 <div class="member-details">
                                    <div></div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/vide.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Victor de Elena</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                                 <div class="member-details">
                                    <div>
                                       <img src="{{ "/assets/img/xprize/team/mama.png" | absolute_url }}" alt="">
                                       <div class="member-info">
                                          <h3>Marina Martinez-Garcia</h3>
                                          <p>Member</p>
                                       </div>
                                    </div>
                                 </div>
                              </li>
                              <!-- /single member row ends -->
                           </ul>
                           <!-- /end team-photos -->
                        </div>
                        <!-- /end col-md-8 -->
                        <div class="pull-left col-md-4 sm-text-center">
                           <div class="team-overview">
                              <h2>Who Are We?</h2>
                              <h3>VALENCIA IA4COVID</h3>
                              <p>This group is made up of more than twenty experts from the Universities and research centers of the Valencian Community and led by Dr. Nuria Oliver. We have all been working intensively since the beginning of the pandemic, altruistically and using the resources available to us in our respective institutions and with the occasional philanthropic collaboration of some companies.</p>
                              <br/>   
                              <p><strong>Affiliated with:</strong> Ellis Alicante, Universitat Politècnica de València, Universitat Jaume I, ELLIS Alicante, ELLIS Alicante, Universitat Politecnica de Valencia, Universitat Jaume I, Universidad Cardenal Herrera CEU, Universidad de Alicante, Universidad Miguel Hernández</p>
                           </div>
                        </div>
                        <!-- /end col-md-4 -->
                     </div>
                     <!-- /end row -->
                  </div>
                  <!-- /end container -->
               </section>
            </section>
         </div>
         <div class="page" id="pOtherInformation"  style="display:none">
            <section class="card ficha">
               <h1>Other Information</h1>
               <p class="center">"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."</p>
               <div class="card ov-overview">
                  <h2>Our Vision</h2>
                  <h3>Subtitulo</h3>
                  <p>Texto plano de lo que se quiere decir</p>
                  <br/>   
               </div>
            </section>
         </div>

         <div class="page" id="pPost1"  style="display:none">
            <section class="card ficha">
               <div class="container">
                  <div class="row">
                     <div class="col-md-2">
                     </div>
                     <div class="col-md-8">
                        <h1 class="xprizetitle">Patterns in reporting data</h1>
                     </div>
                     <div class="col-md-2">
                        <button type="button" class="btn btn-light btnBack" onclick="abrir_panel('pOurApproach')" >GO BACK</button>
                     </div>
                  </div>
                  <div class="row">
                     <div class="col-md-8">
                        <div class="iframewrap1">
                           <iframe frameborder="0" marginheight="0" marginwidth="0" title="" allowtransparency="false" allowfullscreen="true" class="iframe1"  src="xprize_weekday_cases.html"></iframe>
                        </div>
                     </div>
                     <div class="col-md-4">
                        <div class="card post-overview" style="max-height:1111px">
                           <h2>Who Are We?</h2>
                           <h3>VALENCIA IA4COVID</h3>
                           <p>This group is made up of more than twenty experts from the Universities and research centers of the Valencian Community and led by Dr. Nuria Oliver. We have all been working intensively since the beginning of the pandemic, altruistically and using the resources available to us in our respective institutions and with the occasional philanthropic collaboration of some companies.</p>
                           <br/>   
                           <p><strong>Affiliated with:</strong> Ellis Alicante, Universitat Politècnica de València, Universitat Jaume I, ELLIS Alicante, ELLIS Alicante, Universitat Politecnica de Valencia, Universitat Jaume I, Universidad Cardenal Herrera CEU, Universidad de Alicante, Universidad Miguel Hernández</p>
                        </div>
                     </div>
                  </div>
               </div>
            </section>
         </div>
         <div class="page" id="pPost2"  style="display:none">
            <section class="card ficha">
              <div class="row">
                 <div class="col-md-2">
                 </div>
                 <div class="col-md-8">
                    <h1 class="xprizetitle">Detalle 2</h1>
                 </div>
                 <div class="col-md-2">
                    <button type="button" class="btn btn-light btnBack" onclick="abrir_panel('pOurApproach')" >GO BACK</button>
                 </div>
              </div>
               <p class="center">"There is no one who loves pain itself, who seeks after it and wants to have it, simply because it is pain..."</p>
               <div class="card ov-overview">
                  <h2>Our Vision</h2>
                  <h3>Subtitulo</h3>
                  <p>Texto plano de lo que se quiere decir</p>
                  <br/>   
               </div>
            </section>
         </div>
      </div>
   </div>
</div>
<script>
   function abrir_panel(nombrepanel) {
     var i, tabcontent, tablinks;
     tabcontent = document.getElementsByClassName("page");
     for (i = 0; i < tabcontent.length; i++) {
       tabcontent[i].style.display = "none";
     }
     document.getElementById(nombrepanel).style.display = "block";
   }
</script>
