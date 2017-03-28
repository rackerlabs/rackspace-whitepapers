---
title: "White Papers Home | Rackspace Support Network"
permalink: /
layout: whitepaper-home
---
<article>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <div class="container">
      <div class="row content home">
        <section class="featured">
          <h2 class="section-heading">Technical White Papers</h2>
          <p class="tagline"></p>
          <h3 class="featuredHead">Featured White Papers</h3>
          <div class="featured-list">
            {% for featured in site.data.featured %}
              {% for whitepaper in site.pages %}
                {% if whitepaper.permalink == featured.permalink %}
                  <div class="featured">
                    <div class="card blue">
                      <div class="card-content">
                        <div class="card-title">
                          <h4 id="{{ whitepaper.basename }}">{{ whitepaper.title }}</h4>
                        </div>
                        <div class="card-body">
                          <p>{{ whitepaper.description }}</p>
                        </div>
                        <div class="card-link">
                          <p><a href="{{ site.baseurl }}{{ whitepaper.permalink }}">Read the paper</a></p>
                        </div>
                      </div>
                    </div>
                  </div>
                {% endif %}
              {% endfor %}
            {% endfor %}
          </div>
    </section>
        <section class="allContent">
          <div class="allContentTop">
            <div class="allContentHeading">
              <h2 id="top" class="section-heading">All White Papers</h2>
            </div>
            <div class="dropdown">
              <div class="row" id="dropdownRow">
                <div class="col-lg-12">
                  <div class="btn-group">
                    <button id="topics" type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown"><span>Jump to a white paper topic </span><i class="fa fa-caret-down"></i>
                    </button>
                    <ul class="dropdown-menu scrollable-menu" role="menu">
                      {% for category in site.data.categories %}
                        <li><a href="#{{ category.basename }}">{{ category.title }}</a></li>
                      {% endfor %}
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
          {% for category in site.data.categories %}
            <h3 class="topicHead" id="{{ category.basename }}">{{ category.title }}</h3>
            <div class="topicList too-tall">
              <ul class="paperList">
                {% for whitepaper in site.pages %}
                  {% if whitepaper.product == category.title %}
                    {% unless whitepaper.permalink contains "all-whitepapers" %}
                      <li><a href="{{ site.baseurl }}{{ whitepaper.permalink }}">{{ whitepaper.title }}</a></li>
                    {% endunless %}
                  {% endif %}
                {% endfor %}
              </ul>
            </div>
            <div class="show-more">
              <a href="#"><i class="fa fa-chevron-down"></i> <span>View more</span></a>
            </div>
          {% endfor %}
        </section>
      </div>
    </div>
</article>
