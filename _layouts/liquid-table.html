---
layout: default   <!-- parent layout -->
---

<div class="liquid-table-wrapper">
  {% if page.title %}<h1>{{ page.title }}</h1>{% endif %}

  <!-- Render the page content (image + text from the .md file) -->
  <div class="page-content">
    {{ content }}
  </div>

  <!-- Build a comparison table from front matter -->
  {% if page.reynolds or page.gosling %}
  <h2>Comparison</h2>

  <!-- Strengths -->
  {% assign r_str = page.reynolds.strengths | size %}
  {% assign g_str = page.gosling.strengths | size %}
  {% if r_str > g_str %}
    {% assign max_str = r_str %}
  {% else %}
    {% assign max_str = g_str %}
  {% endif %}

  <h3>Strengths</h3>
  <table class="liquid-table">
    <thead>
      <tr>
        <th>Ryan Reynolds</th>
        <th>Ryan Gosling</th>
      </tr>
    </thead>
    <tbody>
      {% for i in (0..max_str | minus: 1) %}
      <tr>
        <td>{{ page.reynolds.strengths[i] | default: "" }}</td>
        <td>{{ page.gosling.strengths[i]  | default: "" }}</td>
      </tr>
      {% endfor %}
    </tbody>
  </table>

  <!-- Weaknesses -->
  {% assign r_weak = page.reynolds.weaknesses | size %}
  {% assign g_weak = page.gosling.weaknesses | size %}
  {% if r_weak > g_weak %}
    {% assign max_weak = r_weak %}
  {% else %}
    {% assign max_weak = g_weak %}
  {% endif %}

  <h3>Weaknesses</h3>
  <table class="liquid-table">
    <thead>
      <tr>
        <th>Ryan Reynolds</th>
        <th>Ryan Gosling</th>
      </tr>
    </thead>
    <tbody>
      {% for i in (0..max_weak | minus: 1) %}
      <tr>
        <td>{{ page.reynolds.weaknesses[i] | default: "" }}</td>
        <td>{{ page.gosling.weaknesses[i]  | default: "" }}</td>
      </tr>
      {% endfor %}
    </tbody>
  </table>
  {% endif %}
</div>

<style>
  .liquid-table-wrapper { margin: 1rem 0; }
  .liquid-table { width: 100%; border-collapse: collapse; margin: .5rem 0 2rem; }
  .liquid-table th, .liquid-table td { border: 1px solid #ddd; padding: .5rem .75rem; vertical-align: top; }
  .liquid-table thead th { text-align: left; }
  .page-content img { max-width: 100%; height: auto; }
</style>
