---
layout: pic
---


<div class="container-fluid index">
    <div class="row">

        <div class="col-md-12 main content-panel">

            <div class="gravatar">
                <img id="bild" src="Anonymous.jpg" class="img-circle about-image" height="150" width="150" alt="{{ site.title }}" />
            </div>
            
            <h1 class="header author-header" itemprop="headline">{{ site.title }}</h1>

            <div class="author-text">
Sehr geehrter Prof. Dr. Quandt,
mit dieser Website möchte ich mich auf eine der ausgeschriebenen 2/3-Stellen im BMBF-geförderten Projekt  „Erkennung, Nachweis und Bekämpfung verdeckter Propaganda-Angriffe über Online-Medien“ bewerben. (Da ich mich relativ kurzfristig entschlossen habe, die Seite aufzusetzen, ist sie nicht ‚auf Hochglanz poliert‘ – insbesondere hatte ich keine Möglichkeit, sie auf iOS-Systemen zu testen. Sollten Probleme mit der Darstellung bestehen, bitte ich daher darum, die Seite am stationären Uni-Rechner mit Firefox, Internet-Explorer oder Chrome aufzurufen.)

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

