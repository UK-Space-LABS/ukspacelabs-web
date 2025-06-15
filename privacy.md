---
layout: default
title: Privacy Policy
subtitle: Your Privacy Matters to Us
---

<section class="privacy-content">
  <h2>Privacy Policy</h2>
  
  <div class="privacy-text">
    <h3>Information We Collect</h3>
    <p>UK Space LABS is committed to protecting your privacy and personal information. This privacy policy outlines how we collect, use, and protect any information you provide when using our website and services.</p>
    
    <p>We may collect the following types of information:</p>
    <ul>
      <li>Contact information including name, email address, and professional affiliation</li>
      <li>Information about your interest in space life sciences and biomedical research</li>
      <li>Professional background and expertise relevant to our mission</li>
      <li>Website usage data and analytics to improve user experience</li>
    </ul>

    <h3>How We Use Your Information</h3>
    <p>The information we collect is used to:</p>
    <ul>
      <li>Facilitate collaboration opportunities within the space life sciences community</li>
      <li>Share relevant research updates, events, and educational opportunities</li>
      <li>Improve our website content and user experience</li>
      <li>Maintain contact with members and stakeholders</li>
      <li>Organize conferences, workshops, and networking events</li>
    </ul>

    <h3>Data Protection and Security</h3>
    <p>We implement appropriate security measures to protect your personal information against unauthorized access, alteration, disclosure, or destruction. Your information is stored securely and access is limited to authorized personnel only.</p>

    <h3>Information Sharing</h3>
    <p>We do not sell, trade, or otherwise transfer your personal information to third parties without your consent, except as outlined in this privacy policy. We may share information with trusted partners who assist us in operating our website or conducting our activities, provided they agree to maintain confidentiality.</p>

    <h3>Your Rights</h3>
    <p>You have the right to:</p>
    <ul>
      <li>Request access to your personal information</li>
      <li>Request correction of inaccurate information</li>
      <li>Request deletion of your personal information</li>
      <li>Opt-out of communications at any time</li>
      <li>Request data portability where applicable</li>
    </ul>

    <h3>Cookies and Website Analytics</h3>
    <p>Our website may use cookies to enhance user experience and collect anonymous usage statistics. You can control cookie settings through your browser preferences.</p>

    <h3>Changes to This Policy</h3>
    <p>We may update this privacy policy from time to time. Any changes will be posted on this page with an updated revision date. We encourage you to review this policy periodically.</p>

    <h3>Contact Us</h3>
    <p>If you have any questions about this privacy policy or how we handle your personal information, please contact us at:</p>
    <p><strong>Email:</strong> <a href="mailto:ukspacelabsengagement@gmail.com">ukspacelabsengagement@gmail.com</a></p>

    <p><em>Last updated: {{ 'now' | date: '%B %d, %Y' }}</em></p>
  </div>
</section>

<section class="hawking-quote">
  <div class="quote-container">
    <img src="{{ 'images/s_hawking_life_in_the_universe.jpg' | relative_url }}" 
         alt="Stephen Hawking quote about life in the universe" 
         class="hawking-quote-img">
  </div>
</section>

<style>
.privacy-content {
  max-width: 800px;
  margin: 0 auto;
  padding: 2rem 0;
}

.privacy-content h2 {
  color: #def3fb !important; /* Brighter */
  text-align: center;
  margin-bottom: 2rem;
  font-size: 2.2rem;
  text-shadow: 0 0 15px rgba(74, 158, 255, 0.6);
}

.privacy-text {
  background: rgba(255, 255, 255, 0.05);
  padding: 2.5rem;
  border-radius: 15px;
  border: 1px solid rgba(255, 255, 255, 0.1);
  line-height: 1.7;
}

.privacy-text h3 {
  color: #4a9eff;
  margin-top: 2rem;
  margin-bottom: 1rem;
  font-size: 1.3rem;
}

.privacy-text h3:first-child {
  margin-top: 0;
}

.privacy-text p {
  color: #e6f3ff;
  margin-bottom: 1.2rem;
  font-size: 1rem;
}

.privacy-text ul {
  color: #e6f3ff;
  margin-bottom: 1.2rem;
  padding-left: 1.5rem;
}

.privacy-text li {
  margin-bottom: 0.5rem;
}

.privacy-text a {
  color: #00d4ff;
  text-decoration: none;
  transition: color 0.3s ease;
}

.privacy-text a:hover {
  color: #4a9eff;
  text-decoration: underline;
}

.hawking-quote {
  margin: 4rem 0;
  text-align: center;
}

.quote-container {
  max-width: 700px;
  margin: 0 auto;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.hawking-quote-img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .privacy-content {
    padding: 1rem;
  }
  
  .privacy-text {
    padding: 1.5rem;
  }
  
  .quote-container {
    padding: 1rem;
  }
}

@media (max-width: 480px) {
  .privacy-text {
    padding: 1rem;
  }
  
  .privacy-text h3 {
    font-size: 1.1rem;
  }
  
  .privacy-text p {
    font-size: 0.9rem;
  }
}
</style>
