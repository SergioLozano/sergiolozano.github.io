---
layout: page
permalink: /resources/
title: resources
description: Here, you can find resources for product marketing, sales enablement, and CX.
nav: true
nav_order: 3
---

This space is packed with templates, frameworks, and kits built from real-world experience in product marketing, sales enablement, and CX. Each resource is field-tested to help you solve problems, align teams, and get better results—faster. Whether you're launching a feature or refining your messaging, these tools are here to save time and bring structure. Scroll down, grab what you need, and make it yours.

---
<!-- Filter Buttons -->
<div style="margin-bottom: 2rem;">
  <strong>Filter by type:</strong>
  <div style="margin-top: 0.5rem;">
    <button class="filter-btn" onclick="filterResources('all')">Show All</button>
    <button class="filter-btn" onclick="filterResources('product-marketing')">Product Marketing</button>
    <button class="filter-btn" onclick="filterResources('sales-enablement')">Sales Enablement</button>
    <button class="filter-btn" onclick="filterResources('customer-experience')">Customer Experience</button>
  </div>
</div>

<!-- RESOURCE SECTIONS -->

<!-- PRODUCT MARKETING -->
<div class="resource-group product-marketing">
  <h2>Resources for Product Marketing</h2>
  <div style="display: flex; gap: 1rem; align-items: flex-start; margin-bottom: 2rem;">
    <img src="/assets/img/thumbnail-product-launch-brief-gtm-strategy.jpg" alt="Icon in beige of a presentation" style="width: 120px; height: auto; border: 1px solid #ccc;" />
    <div>
      <h3>Template for Product Launch Brief & GTM Strategy</h3>
      <p style="font-size: 0.95rem;">This comprehensive slide-based product launch template includes both content structure and instructions to guide anyone, from junior to senior PMMs, through the end-to-end launch process.</p>
      <p style="font-size: 0.95rem;">Perfect for tech companies and adaptable to both sales-led and product-led organizations. Download and customize the PPTX file or preview the template in PDF.</p>
      <a href="https://sergiolozano.com/assets/resources/template-product-launch-brief-gtm-strategy.pdf" class="btn btn--primary">View PDF</a>
      <a href="https://sergiolozano.com/assets/resources/template-product-launch-brief-gtm-strategy.pptx" class="btn">Download PPTX</a>
    </div>
  </div>

  <div style="display: flex; gap: 1rem; align-items: flex-start; margin-bottom: 2rem;">
    <img src="/assets/img/thumbnail-release-scope.jpg" alt="Icon in beige of a presentation" style="width: 120px; height: auto; border: 1px solid #ccc;" />
    <div>
      <h3>Template for Release Scope</h3>
      <p style="font-size: 0.95rem;">This template helps you clarify what’s in and out of scope for each product release. Ideal for gathering inputs from Product Managers and ensuring marketing clarity.</p>
      <p style="font-size: 0.95rem;">Includes a pre-filled example. Download and customize the PPTX or preview the PDF.</p>
      <a href="https://sergiolozano.com/assets/resources/template-release-scope.pdf" class="btn btn--primary">View PDF</a>
      <a href="https://sergiolozano.com/assets/resources/template-release-scope.pptx" class="btn">Download PPTX</a>
    </div>
  </div>
</div>



<!-- SALES ENABLEMENT -->
<div class="resource-group sales-enablement">
  <h2>Resources for Sales Enablement</h2>
  <div style="display: flex; gap: 1rem; align-items: flex-start; margin-bottom: 2rem;">
    <img src="/assets/img/thumbnail-one-pager-sales-enablement.jpg" alt="Icon of a file" style="width: 120px; height: auto; border: 1px solid #ccc;" />
    <div>
      <h3>Template for Sales One-Pager</h3>
      <p style="font-size: 0.95rem;">A concise one-pager to support sales conversations, summarizing product value, use cases, objection handling, and key messaging.</p>
      <a href="https://sergiolozano.com/assets/resources/template-one-pager-for-use-cases-sales-conversations.pdf" class="btn btn--primary">View PDF</a>
      <a href="https://sergiolozano.com/assets/resources/template-one-pager-for-use-cases-sales-conversations.docx" class="btn">Download DOCX</a>
    </div>
  </div>

  <div style="display: flex; gap: 1rem; align-items: flex-start; margin-bottom: 2rem;">
    <img src="/assets/img/thumbnail-competitor-battlecard.jpg" alt="Battlecard icon" style="width: 120px; height: auto; border: 1px solid #ccc;" />
    <div>
      <h3>Template for Competitor Battlecards</h3>
      <p style="font-size: 0.95rem;">This battlecard template helps sellers position your product effectively against competitors. Includes SWOT, value differentiators, and talk tracks.</p>
      <p style="font-size: 0.95rem;">Download and customize to fit your sales motion.</p>
      <a href="https://sergiolozano.com/assets/resources/template-competitor-battlecard.pdf" class="btn btn--primary">View PDF</a>
      <a href="https://sergiolozano.com/assets/resources/template-competitor-battlecard.pptx" class="btn">Download PPTX</a>
    </div>
  </div>
</div>



<!-- CUSTOMER EXPERIENCE -->
<div class="resource-group customer-experience">
  <h2>Resources for Customer Experience</h2>
  <div style="display: flex; gap: 1rem; align-items: flex-start; margin-bottom: 2rem;">
    <img src="/assets/img/thumbnail-customer-journey-map-carrousel.jpg" alt="Customer Journey Map thumbnail" style="width: 120px; height: auto; border: 1px solid #ccc;" />
    <div>
      <h3>Customer Journey Map for B2B SaaS</h3>
      <p style="font-size: 0.95rem;">A journey map for visualizing every stage of your customer lifecycle—from awareness to expansion. Tailored for hybrid GTM models.</p>
      <a href="https://www.figma.com/community/file/1502648775036013780/customer-journey-map-b2b-saas-products" class="btn btn--primary">View Template in Figma</a>
    </div>
  </div>
</div>

<!-- JavaScript Filtering Logic -->
<script>
function filterResources(category) {
  const groups = document.querySelectorAll('.resource-group');
  groups.forEach(group => {
    if (category === 'all' || group.classList.contains(category)) {
      group.style.display = 'block';
    } else {
      group.style.display = 'none';
    }
  });
}
</script>


<!-- Optional Styling for Buttons filter -->
<style>
.filter-btn {
  padding: 0.3rem 0.6rem;
  margin-right: 0.5rem;
  background-color: #eee;
  border: 1px solid #ccc;
  border-radius: 6px;
  cursor: pointer;
  font-size: 0.8rem;
}
.filter-btn:hover {
  background-color: #ddd;
}
</style>

<!-- Optional Styling for Headers -->
<style>
h2 {
  font-size: 1.4rem;
  font-weight: bold;
  margin-bottom: 1rem;
}

h3 {
  font-size: 1.1rem;
  font-weight: bold;
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}
</style>

<!-- Optional Styling for Buttons -->
<style>
.btn {
  padding: 0.54rem 1.14rem;
  border-radius: 0.5rem;
  font-size: 0.71rem;
}
</style>