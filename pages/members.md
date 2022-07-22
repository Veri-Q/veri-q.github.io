---
title: Members
layout: page
permalink: /members/
#menubar: menu_members
hero_height: custom
---

<style>
.aa-link {
    color: #438ca9;
}
.custom-width {max-width: 800px}
.hero.custom {
    padding: 1.25rem;
}
.icon.custom {
    width: 7.5rem;
    height: 7.5rem;
    margin-bottom: 1rem;
    border-radius: 50%;
    overflow: hidden;
}
</style>

<center>
{% assign callouts=site.data.callout_coodinators %}
<section class="hero {% if callouts.height %} {{ callouts.height }} {% else %} is-medium {% endif %} custom-width">
    <div class="hero-body">
        <div class="container">
            <p class="is-4 has-text-centered">
                    <span> Coodinators (by alphabets) </span>
            </p>
            <div class="columns is-multiline is-centered">
                {% for callout in callouts.items %}
                    <div class="column is-4 has-text-centered">
                        {% if callout.link %}<a href=" {{ callout.link }}">{% endif %}
                        <div class="icon custom">
                            {% if callout.icon %}
                            <img src="{{callout.icon}}">
                            {% else %}
                            <i class="fas fa-user-circle"></i>
                            {% endif %}
                        </div>
                        <p class="title is-5">{{ callout.title }}</p>
                        <p class="subtitle is-5">{{ callout.subtitle }}</p>
                        {% if callout.link %}</a>{% endif %}

                        {% if callout.description %}
                        <div class="content">
                            <p>{{ callout.description | newline_to_br }}</p>
                        </div>
                        {% endif %}

                        {% if callout.call_to_action_name %}
                        <a href="{{ callout.call_to_action_link | relative_url }}" class="button is-primary">
                            {{ callout.call_to_action_name }}
                        </a>
                        {% endif %}
                    </div>
                {% endfor %}
            </div>
        </div>
    </div>
</section>

{% assign callouts=site.data.callout_contributors %}
<section class="hero {% if callouts.height %} {{ callouts.height }} {% else %} is-medium {% endif %} custom-width">
    <div class="hero-body">
        <div class="container">
            <p class="is-4 has-text-centered">
                    <span> Contributors (by alphabets) </span>
            </p>
            <div class="columns is-multiline is-centered">
                {% for callout in callouts.items %}
                    <div class="column is-4 has-text-centered">
                        {% if callout.link %}<a href=" {{ callout.link }}">{% endif %}
                        <div class="icon custom">
                            {% if callout.icon %}
                            <img src="{{callout.icon}}">
                            {% else %}
                            <i class="fas fa-user-circle fa-4x"></i>
                            {% endif %}
                        </div>
                        <p class="title is-5">{{ callout.title }}</p>
                        <p class="subtitle is-5">{{ callout.subtitle }}</p>
                        {% if callout.link %}</a>{% endif %}
                        
                        {% if callout.description %}
                        <div class="content">
                            <p>{{ callout.description | newline_to_br }}</p>
                        </div>
                        {% endif %}

                        {% if callout.call_to_action_name %}
                        <a href="{{ callout.call_to_action_link | relative_url }}" class="button is-primary">
                            {{ callout.call_to_action_name }}
                        </a>
                        {% endif %}
                    </div>
                {% endfor %}
            </div>
        </div>
    </div>
</section>
</center>
