---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2 class="cvsection"> Academic experience</h2>

<table style="width:100%">
  <tr>
    <td class="left">2015-now</td>
    <td class="right"><b>Postdoctoral Fellow</b> <br> <a class="cvlink"
     href="http://www.nespmarine.edu.au" target="_blank">NESP Marine Biodiversity Hub</a><br>Centre for Marine Futures & School of Biological Sciences, University of Western Australia, Perth, Australia</td>
  </tr>

</table>

<h2 class="cvsection"> Education</h2>


<table style="width:100%">
  <tr>
    <td class="left">2011-15</td>
    <td class="right"><b>Ph.D Marine Ecology</b>, University of Western Australia <span class="cvlocation">[Perth, Australia]</span><br>
    <a class="cvlink" href="http://research-repository.uwa.edu.au/en/publications/submarine-topography-as-a-predictor-of-mobile-predator-hotspots-relevance-and-applications-to-conservation-planning-in-the-pelagic-ocean(b0d4da3f-49bd-404f-bd73-0b5dfbcc2746).html" target="_blank">Submarine topography as a predictor of mobile predator hotspots: Relevance and applications to conservation planning in the pelagic ocean</a><br>
    <a class="cvlink" href="https://www.youtube.com/watch?v=9LrH0SmIPp4" target="_blank">Valedictorian</a> - UWA March 2016 graduation</td>
  </tr>
  <tr>
    <td class="left">2008-09</td>
    <td class="right"><b>M.Res Marine Mammal Science (1st class)</b>, University of St Andrews <span class="cvlocation">[St Andrews, Scotland]</span><br>
    Don't count your whales before they migrate: Using aerial surveys to assess the status of breeding stock 'D' humpback whales (<em>Megaptera novaeangliae</em>) in Western Australia<br>
    Associated paper: <a class="cvlink" href="https://phbouchet.github.io/publications/2012-Salgado-Humpbacks">Salgado <em>et al.</em> 2012.&nbsp;JCRM 12(1): 29-38.</a></td>
  </tr>
  <tr>
    <td class="left">2008</td>
    <td class="right"><b>Marine Mammal Management course</b>, Nova Southeastern University <span class="cvlocation">[Fort-Lauderdale-Davie, FL, USA]</span></td>
  </tr>
  <tr>
    <td class="left">2006-07</td>
    <td class="right"><b>M.Sc Marine and Coastal Sciences</b>, University of Western Brittany <span class="cvlocation">[Brest, France]</span></td>
  </tr>
  <tr>
    <td class="left">2003-06</td>
    <td class="right"><b>B.Sc (Hons. 1st class) Zoology</b>, University of Western Brittany <span class="cvlocation">[Brest, France]</span></td>
  </tr>
</table>


<h2 class="cvsection"> Field experience</h2>

<table style="width:100%">
  <tr>
    <td class="left">2017</td>
    <td class="right"><span class="cvrole">Research scientist</span><br>
    Pelagic videography survey of Ascension Island waters.<br>
    <span class="cvwho">Ascension Island Government</span></td>
  </tr>

  <tr>
    <td class="left">2014</td>
    <td class="right"><span class="cvrole">Research scientist</span><br>
    Pelagic videography survey of Rapa Iti, French polynesia<br>
    <span class="cvwho">National Geographic Society Pristine Seas Programme</span></td>
  </tr>

  <tr>
    <td class="left">2012</td>
    <td class="right"><p class="ptop"><span class="cvrole">Research scientist</span><br>
    Oceanic Shoals Marine Biodiversity Survey, Timor Sea.<br>
    <span class="cvwho">National Environmental Research Program (NERP) Marine Biodiversity Hub</span></p>

    <p class="pbottom"><span class="cvrole">Field assistant</span><br>
    Rowley Shoals reef shark tagging programme<br>
    <span class="cvwho">Australian Institute of Marine Science (AIMS)</span></p>

    </td>
  </tr>

  <tr>
    <td class="left">2010-12</td>
    <td class="right"><span class="cvrole">Assistant field coordinator</span><br>
    Theodolite tracking of cetaceans in Geographe Bay, W Australia<br>
    <span class="cvwho">Southwest Whale Ecology Study (SouWEST)</span></td>
  </tr>

  <tr>
    <td class="left">2007-11</td>
    <td class="right"><span class="cvrole">Research and field assistant</span><br>
    Humpback whale (<em>Megaptera novaeangliae</em>) abundance estimation and population modelling<br>
    Pygmy blue whale (<em>Balaenoptera musculus brevicauda</em>) photo-identification and satellite tracking<br>
    <span class="cvwho">Centre for Whale Research (WA) Inc. (CWR)</span></td>
  </tr>

  <tr>
    <td class="left">2006</td>
    <td class="right"><span class="cvrole">Research assistant</span><br>
    Impact of vessel traffic on the haul-out behaviour of grey seals (<em>Halichoerus grypus</em>) in the Molène Archipelago<br>
    <span class="cvwho">Marine Mammal Research Laboratory of Oceanopolis</span></td>
  </tr>

  <tr>
    <td class="left">2004</td>
    <td class="right"><span class="cvrole">Field assistant</span><br>
    Blue whale (<em>Balaenoptera musculus</em>) habitat use and feeding strategies<br>
    <span class="cvwho">Mingan Island Cetacean Study (MICS)</span></td>
  </tr>

  </table>


<h2 class="cvsection"> Publications</h2>

<table style="width:100%">
  <tr>
    <td class="left">2017</td>
    <td class="right"><ul class="cvpublist">{% for post in site.publications reversed %}

      {% capture pubyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if pubyear == "2017" %}

      {% include archive-single-cv.html %}

      {% endif %}

    {% endfor %}
    </ul>
    </td>
  </tr>



  <tr>
    <td class="left">2015</td>
    <td class="right"><ul class="cvpublist">{% for post in site.publications reversed %}

      {% capture pubyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if pubyear == "2015" %}

      {% include archive-single-cv.html %}

      {% endif %}

    {% endfor %}
    </ul>
    </td>
  </tr>

  <tr>
    <td class="left">2013</td>
    <td class="right"><ul class="cvpublist">{% for post in site.publications reversed %}

      {% capture pubyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if pubyear == "2013" %}

      {% include archive-single-cv.html %}

      {% endif %}

    {% endfor %}
    </ul>
    </td>
  </tr>

  <tr>
    <td class="left">2012</td>
    <td class="right"><ul class="cvpublist">{% for post in site.publications reversed %}

      {% capture pubyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if pubyear == "2012" %}

      {% include archive-single-cv.html %}

      {% endif %}

    {% endfor %}
    </ul>
    </td>
  </tr>

  <tr>
    <td class="left">2011</td>
    <td class="right"><ul class="cvpublist">{% for post in site.publications reversed %}

      {% capture pubyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if pubyear == "2011" %}

      {% include archive-single-cv.html %}

      {% endif %}

    {% endfor %}
    </ul>
    </td>
  </tr>

</table>

<h2 class="cvsection"> Grants and awards</h2>

<ul class="cvgrantslist">{% for post in site.grants reversed%}
  {% include archive-single-grant-cv.html %}
{% endfor %}</ul>


<h2 class="cvsection"> Talks and conference presentations</h2>

<table style="width:100%">
  <tr>
    <td class="left">2016</td>
    <td class="right">{% for post in site.talks reversed%}

      {% capture talkyear %}{{ post.date | date: '%Y' }}{% endcapture %}

      {% if talkyear == "2016" %}

        {% include archive-single-talk-cv.html %}

      {% endif %}

    {% endfor %}

    </td>
  </tr>

</table>


  <h2 class="cvsection"> Teaching and outreach</h2>

  <table style="width:100%">
    <tr>
      <td class="left">2013</td>
      <td class="right"><span class="cvrole">Photography laboratory supervisor</span><br>
      <span class="cvwho">Curtin University of Technology, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2012</td>
      <td class="right"><span class="cvrole">Teaching assistant and science communication tutor</span><br>
      <span class="cvwho">University of Western Australia, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2011-13</td>
      <td class="right"><span class="cvrole">R demonstrator and teaching assistant</span><br>
      <span class="cvwho">University of Western Australia, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2011</td>
      <td class="right"><span class="cvrole">Workshop coordinator and demonstrator</span><br>
      <span class="cvwho">Murdoch University, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2010-11</td>
      <td class="right"><span class="cvrole">Marine tour guide and sales assistant</span><br>
      <span class="cvwho">Oceanic cruises (Rottnest Express), Fremantle, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2006</td>

      <td class="right"><p class="ptop"><span class="cvrole">Marine education assistant</span><br>
      <span class="cvwho">Association Picardie Nature, Somme Bay, France</span></p>

      <p class="pbottom"><span class="cvrole">Marine education and animal care assistant</span><br>
      <span class="cvwho">Oceanopolis seal rescue and rehabilitation centre, Brest, France</span></p>
      </td>
    </tr>

</table>

  <h2 class="cvsection"> Professional experience</h2>

  <table style="width:100%">
    <tr>
      <td class="left">2012-13</td>
      <td class="right"><span class="cvrole">Library officer</span><br>
      <span class="cvwho">University of Western Australia, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2011</td>
      <td class="right"><span class="cvrole">Administrative assistant</span><br>
      <span class="cvwho">University of Western Australia, Perth, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2010</td>
      <td class="right"><span class="cvrole">Data manager assistant</span><br>
      <span class="cvwho">Macquarie University, Sydney, Australia</span></td>
    </tr>

    <tr>
      <td class="left">2009</td>
      <td class="right"><span class="cvrole">IT consultant and computer programmer</span><br>
      <span class="cvwho">TMF Group, Geneva, Switzerland</span></td>
    </tr>

    <tr>
      <td class="left">2007-08</td>
      <td class="right"><span class="cvrole">IT analyst and reporting manager assistant</span><br>
      <span class="cvwho">Kemnay Services Ltd., Geneva, Switzerland</span></td>
    </tr>
</table>
