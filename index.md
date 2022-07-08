---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: VeriQ
subtitle: Verification Toolchain for Quantum Computing
layout: page
#callouts: home_callouts
#show_sidebar: true
hero_height: 400px
---

<style>
.aa-link {
    color: #438ca9;
}
.custom-width {max-width: 800px}
</style>

<center>
<p align="left" class="custom-width">
<font size="5">
VeriQ is a toolchain for verification of quantum computing, focusing on the following three aspects:
</font>
</p>
{% assign callouts=site.data.callout_tools %}
<section class="hero {% if callouts.height %} {{ callouts.height }} {% else %}is-medium {% endif %} custom-width">
    <div class="hero-body">
        <div class="container">
            <div class="columns is-multiline is-centered">
                {% for callout in callouts.items %}
                    <div class="column is-4 has-text-centered">
                        <a href="{{ callout.call_to_action_link | relative_url }}" class="aa-link">
                        {% if callout.icon %}
                        <div class="icon callout-icon">
                        {% if callout.icon_brand %}
                            <i class="fab {{ callout.icon }} fa-4x"></i>
                        {% else %}
                            <i class="fas {{ callout.icon }} fa-4x"></i>
                        {% endif %}
                        </div>
                        {% endif %}
                        </a>
                        <p class="title is-5">{{ callout.title }}</p>
                        <p class="subtitle is-5">{{ callout.subtitle }}</p>
                        {% if callout.description %}
                        <div class="content">
                            <p>{{ callout.description | newline_to_br }}</p>
                        </div>
                        {% endif %}
                    </div>
                {% endfor %}
            </div>
        </div>
    </div>
<hr>
</section>
</center>

<center>

<p class="title is-4 custom-width" align="left">Latest News</p>

<div class="columns is-multiline custom-width">
    {% for post in site.posts limit:3 %}
    <div class="column is-12">
        {% include post-card.html %}
    </div>
    {% endfor %}
</div>
</center>