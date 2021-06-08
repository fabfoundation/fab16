---
layout: page-fullwidth
title: Program
lang: en
permalink: /program/

programtitle: Program
programsubtitle: ""
programimg: ""

title_text: "Program"
subtitle_text: ""
color_class: "colorblue"
img: "assets/img/FabTrends.jpg"
programheader: "<strong style='font-size:22px;'>Be part of the largest conference on digital fabrication in the world.</strong>
                 <br><br>
                 Join us in Montréal, Canada, and online, for the annual meeting of the international Fab Labs network, a hybrid and distributed event!
                <br><br>
                Join world-class panelists, members of the Fab Lab community, makers from all over the world and professionals from all kinds of fields in the annual Fab Lab Conference and the Fab Festival in Montréal, Canada, in August 2021<span class='line hidden'>from August 9 to August 15</span>, combined with the Fab City Summit<span class='line hidden'>, from August 13 to August 15</span>. Attend world-class panels, demos, workshops, discussions and lab presentations from representatives from all over the globe!
                <br><br>"
programdesc: "<br><br>
                <strong style='' class='travelmenu'>Fab Lab Conference <span class='line hidden'>from 9 to 12 August</span></strong>
                <br><br>
                Conference on the state of the Fab Labs network and the impacts of the Fab Labs movement.<br>
                Prospective conferences<br>
                <ul>
                    <li>Latest digital manufacturing and machining methods</li>
                    <li>Innovative approaches at the level of materials and matter</li>
                    <li>Speakers and panelists on the theme and topics of the FAB16</li>
                </ul>
                Hands-on and theoretical workshops<br>
                Research presentations<br>
                Challenges<br>
                Networking highlights<br>
                The Academany graduation ceremony<br>
                Mobile Fab Labs<br>
                <br><br>
                "
programdesc2: "<br><br>
                <strong style='' class='travelmenu'>Fab Festival <span class='line hidden'>- August 14th</span></strong>
                <br><br>
                The Fab Festival is a Saturday event that follows the structure of the main event, but with activities, adapted for the general public and children, offered by Fab Labs around the country.<br>
                <ul>
                    <li>Interactive fair of inspiring projects</li>
                    <li>Conferences</li>
                    <li>Demonstrations</li>
                </ul>
                <br><br>
                <strong style='' class='travelmenu'>The Fab City Summit <span class='line hidden'>from August 13 to August 15</span></strong>
                <br><br>
                A three-day series of conferences and workshops offered by world and local luminaries that highlight the global issues facing cities and territories and the concrete initiatives surrounding the growth of Fab Cities.
                <br><br><br>
                <strong style='' class='travelmenu'>Fab City Campus <span class='line hidden'>from August 12 to August 19</span></strong>
                <br><br>
                A short term intervention, three days, which will highlight local and international experiences and Fab City prototypes. It will include exhibits, tours of local Fab Labs and fabricating workshops.<br>
                "
program: ""
img_programmation: "assets/img/programmation.jpg"
pdf_programmation: "assets/downloads/FAB16_FABCITYSummit_PROGRAMMATION.pdf"
pdf_programmation_text: "Download PDF"
afterimg: "You will be able to follow the full schedule details, links, tutors, registration and much more, by registering on our online platform here : "
afterimglink: "<a href='https://live.fablabs.io/' target='_blank'>live.fablabs.io</a>"


---
<section class="no-padding" id="" style="padding: 25px 50px 50px 50px;">
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-6">
                <img src="{{ page.img | relative_url}}" class="img-responsive" alt="{{ page.title}}" width="960" height="382">
            </div>
            <div class="col-lg-6">
                <p class="{{ color_class }}">{{page.programheader}}</p>
            </div>
        </div>
    </div>
</section>

<section class="no-padding" id="" style="padding: 25px 50px 50px 50px;">

    <div class="container-fluid">
        <div class="row">
            
            <div class="col-lg-12 col-md-12">

                <img src="{{ page.img_programmation | relative_url}}" class="img-responsive" style="margin:auto;" alt="{{ page.title}}">
            
            </div>
            <div class="col-lg-12 col-md-12">
                
                <p class="{{ color_class }} text-center">
                    <br>
                    <a href="{{ site.url }}/{{page.pdf_programmation}}" target="_blank" download="FAB16_FABCITYSummit_PROGRAMMATION">{{page.pdf_programmation_text}}</a>
                </p>

            </div>
            
            <div class="col-lg-12 col-md-12">

                <br><br>
                <p class="{{ color_class }} text-center">{{page.afterimg}}</p>

                <div class="row no-gutter comingsoon text-center pad25 backwhite">
                    {{page.afterimglink}}
                </div>
            </div>
        </div>
    </div>

</section>

