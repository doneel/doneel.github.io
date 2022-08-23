---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landing
title: Daniel O'Neel
---

<div id="landing">
  <div id="about-container">
    <h3>About</h3>
    <div id="about-content">
      <p>
        I write about tech, politics, faith, and Tolkien.
      </p>
      <br>
      <p>
        I'm on the founding team at <a href="https://www.joinsherlock.com/">Sherlock Retirement</a>.
      </p>
      <p>
        Before that I was a team lead at <a href="https://www.wealthfront.com/">Wealthfront</a>.
      </p>
      <p>
        Before that I was Editor-in-chief at the <a href="https://stanfordreview.org/">Stanford Review</a>.
      </p>
    </div>
  </div>
  <div id="writing-container">
    <h3>Writing</h3>
      {% for category in site.categories %}
        {% capture category_name %}{{category | first }}{% endcapture %}
        <h5>{{ category_name }}</h5>
        <ul class="posts">
          {% for post in site.categories[category_name] %}
            <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
          {% endfor %}
        </ul>
      {% endfor %}
  </div>
</div>
