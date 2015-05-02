---
layout: home
---
>Faye: I can’t be stuck in one place for long—it’ll kill me. My whole family’s like that.

>Spike: Yeah right.

>Faye: We’re Romanies. For eons we’ve wandered the stars looking for love. It’s our way.

>Spike: Huh?

>Faye: You don’t know anything, do you? Romanies are gypsies. And you know what we call someone like you? A gaucho, that means a bumpkin that doesn’t know which way is up.

>Spike: Gaucho. I like that.

>Faye: [howls] The wilds are calling me! You can’t keep me locked up!


 *Cowboy Bebop* 

<!-- {% for post in paginator.posts %}
<div class="row-fluid">
  <div class="span12">
    <h2>{{ post.title | truncatewords: 10 | capitalize }}</h2>
    <h4>{{ post.date | date_to_long_string }}</h4>
    <p>
      <a href="{{ post.url }}">Read Post</a>
    </p>
  </div>
</div>

{% endfor %}

<div class="row-fluid">
  <div class="span12">
    <div class="pagination">
      <ul>
        {% if paginator.previous_page %}
          {% if paginator.previous_page == 1 %}
          <li><a href="/">Prev</a></li>
          {% else %}
          <li><a href="/page{{ paginator.previous_page }}">Prev</a></li>
          {% endif %}
        {% else %}
        <li><span class="disabled">Prev</span></li>
        {% endif %}
        {% if paginator.page == 1 %}
        <li><span class="active">1</span></li>
        {% else %}
        <li><a href="/">1</a></li>
        {% endif %}
        {% for count in (2..paginator.total_pages) %}
          {% if count == paginator.page %}
          <li><span class="active">{{ count }}</span></li>
          {% else %}
          <li><a href="/page{{ count }}">{{ count }}</a></li>
          {% endif %}
        {% endfor %}
        {% if paginator.next_page %}
        <li><a href="/page{{ paginator.next_page }}">Next</a></li>
        {% else %}
        <li><span class="disabled">Next</span></li>
        {% endif %}
      </ul>
    </div>
  </div>
</div> -->