---
permalink: /components/other/labels/
layout: styleguide
type: component
title: Labels
lead: See <a href="https://standards.usa.gov/labels/">US Web Design Standards</a> for design and accessbiility description.
---

<div class="preview">

  <h6>Small</h6>
  <span class="usa-label">New</span>

  <h6>Large</h6>
  <span class="usa-label-big">New</span>

  <h6>Small surrounded by &lt;a href="#"&gt;|&lt;/a&gt;</h6>
  <a href="#"><span class="usa-label">New</span></a>

</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="false" aria-controls="collapsible-0">
    PHP Usage
  </button>
  <div id="collapsible-0" aria-hidden="true" class="usa-accordion-content">
<pre><code class="language-php">// render unescaped HTML string
echo SAMUIKit\Other::label($config)</code></pre>
  </div>
</div>

<div class="usa-accordion-bordered usa-accordion-docs">
  <button class="usa-button-unstyled usa-accordion-button"
      aria-expanded="true" aria-controls="collapsible-0">
    Documentation
  </button>
  <div id="collapsible-0" aria-hidden="false" class="usa-accordion-content">
    <h4 class="usa-heading">Labels</h4>
    <h5>Required keys</h5>
    <ul>
      <li><strong>title:</strong> The text to display within the label.</li>
    </ul>
    <h5>Optional keys</h5>
    <ul>
      <li><strong>big:</strong> true|false (default is false). Whether to use the "big" label from USWDS or not.</li>
      <li><strong>surround:</strong> HTML string, separated by a vertical bar to wrap the label span in.</li>
    </ul>
    <h5>Keys being reconsidered</h5>
    <ul>
      <li><strong>moreClass:</strong> Extra classes to add to the label span.</li>
      <li><strong>background:</strong> Class name for background color.</li>
      <li><strong>icon:</strong> Approved font-awesome icon to include. See Icon.</li>
    </ul>
  </div>
</div>
