---
layout: pic
---


<div class="container-fluid index">
    <div class="row">

        <div class="col-md-12 main content-panel">

            <div class="gravatar">
                <!-- img id="bild" src="Anonymous.jpg" class="img-circle about-image" height="150" width="150" alt="{{ site.title }}" / -->
                <img id="bild" src="Bewerbung_image.jpg" class="img-circle about-image" height="150" width="150" alt="{{ site.title }}" />
            </div>
            
            <h1 class="header author-header" itemprop="headline" style="font-size:2.75em;">Mehr Informationen gefällig?</h1>

            <div class="author-text">
<p align="left">Sehr geehrte Damen und Herren,</p>

<p align="left">diese Website soll dazu dienen, dass Sie sich ein umfassendes Bild von mir und meinen Qualifikationen machen können.</p>

<p align="left">Über die Navigationsleiste oben links gelangen Sie zu Informationen zu meinen momentanen wissenschaftlichen Projekten (inkl. der daraus bislang hervorgegangenen Publikationen) und zu meiner Lehrerfahrung. Außerdem stehen Ihnen unter ‚Anlagen‘ alle meine bislang erworbenen Zeugnisse und Zertifikate sowie ein ausführlicher tabellarischer Lebenslauf zum Download zur Verfügung.</p>

<p align="left"> Freundliche Grüße und hoffentlich bis bald</p>

<p align="left"> Annika Hamachers</p>
            </div>

            {% include social_links.html %}
          </div>
         <!-- <div class="col-md-12 main content-panel">

            <div class="articles">

              <h2>Latest Articles</h2>

              <ul>
                  {% for post in site.posts | limit: site.post_limit %}

                      <li>
                          <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
                          <small class="hidden-xs">{{ post.date | date: "%B %-d, %Y" }}</small>
                      </li>

                  {% endfor %}
                  <li>
                      <small><i><a href="{{ site.baseurl }}/posts/">more...</a></i></small>
                  </li>
              </ul>

            </div>

        </div>-->

    </div>
</div>

