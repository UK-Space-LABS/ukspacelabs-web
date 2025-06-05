---
layout: landing
theme: Home
title: UK-Space-LABS
logo: ![UK-Space-LABS logo](images/Space_Logo_col_dEC_14.jpg)
subtitle: Welcome - The UK Space Life and Biomedical Sciences Association

partners:
- name: UK Space Agency (UKSA)
  logo_path: images/partner_logos/uksa_logo.png
  ref_url: https://www.gov.uk/government/organisations/uk-space-agency
- name: Royal Aeronautical Society (RAeS)
  logo_path: images/partner_logos/raes_logo.png
  ref_url: https://www.aerosociety.com/
- name: Aerospace Medical Association (AsMA)
  logo_path: images/partner_logos/asma_logo.png
  ref_url: https://www.asma.org/
- name: Blue Abyss
  logo_path: images/partner_logos/blue_abyss_logo.png
  ref_url: https://www.blueabyss.uk/
--- 

<!-- under_construction parameter set to 'true' in the _config.yaml -->
{% if site.under_construction %}
<!-- Maintenance mode is handled in the main_page layout -->
{% else %}

<section class="about-section" id="about">
  <h2>🚀 About UK Space LABS</h2>
  
  <p>{{ site.about-author }} exists to optimise <strong>communication, cooperation and collaboration (C3)</strong> between UK based organisations and individuals and foreign entities involved in research, healthcare, commerce, education and outreach activities related to space life and biomedical sciences and the human element of human spaceflight.</p>
  
  <p>The Association aims to enhance the practice, output and benefits of the Space Life and Biomedical Sciences field of endeavour in the UK and contribute to the development and translation of space science and services to terrestrial needs.</p>
  
  <p>Furthermore, UK Space LABS aims to create educational, research and career opportunities for students and professionals of the UK who are interested in space life and biomedical sciences and shall promote UK involvement in human spaceflight as a means of enhancing and strengthening the academic, scientific, industrial and economic foundations of the UK.</p>
  
  <p>UK Space LABS will also promote the establishment of harmonised space biomedicine education globally and to propel the progression of this multidisciplinary field.</p>
</section>

<section class="content-section" id="mission">
  <h2>🌟 Our Mission</h2>
  
  <div class="mission-grid">
    <div class="mission-item">
      <div class="mission-icon">
        <i class="fa fa-users" aria-hidden="true"></i>
      </div>
      <h3>Collaboration</h3>
      <p>Building bridges between UK organisations and international partners in space life sciences and biomedical research.</p>
    </div>
    
    <div class="mission-item">
      <div class="mission-icon">
        <i class="fa fa-graduation-cap" aria-hidden="true"></i>
      </div>
      <h3>Education</h3>
      <p>Creating educational and career opportunities for students and professionals interested in space biomedicine.</p>
    </div>
    
    <div class="mission-item">
      <div class="mission-icon">
        <i class="fa fa-rocket" aria-hidden="true"></i>
      </div>
      <h3>Innovation</h3>
      <p>Promoting UK involvement in human spaceflight and advancing space science applications for terrestrial needs.</p>
    </div>
  </div>
</section>

<section class="team-section" id="team">
  <h2>👥 Our Team</h2>
  
  {% if site.chair %}
  <div class="team-category">
    <h3>Chair</h3>
    <div class="team-grid">
      {% for member in site.chair %}
      <div class="team-member">
        <h4>{{ member.name }}</h4>
        <p class="member-role">{{ member.role }}</p>
        <p class="member-affiliate">{{ member.affiliate }}</p>
        {% if member.social_handler %}
        <p class="member-social">{{ member.social_handler }}</p>
        {% endif %}
      </div>
      {% endfor %}
    </div>
  </div>
  {% endif %}
  
  {% if site.co-ordinators %}
  <div class="team-category">
    <h3>Co-ordinators</h3>
    <div class="team-grid">
      {% for member in site.co-ordinators %}
      <div class="team-member">
        <h4>{{ member.name }}</h4>
        <p class="member-role">{{ member.role }}</p>
        <p class="member-affiliate">{{ member.affiliate }}</p>
        {% if member.social_handler %}
        <p class="member-social">{{ member.social_handler }}</p>
        {% endif %}
      </div>
      {% endfor %}
    </div>
  </div>
  {% endif %}
  
  {% if site.web_development %}
  <div class="team-category">
    <h3>Web Development</h3>
    <div class="team-grid">
      {% for member in site.web_development %}
      <div class="team-member">
        <h4>{{ member.name }}</h4>
        <p class="member-role">{{ member.role }}</p>
        <p class="member-affiliate">{{ member.affiliate }}</p>
        {% if member.social_handler %}
        <p class="member-social">{{ member.social_handler }}</p>
        {% endif %}
      </div>
      {% endfor %}
    </div>
  </div>
  {% endif %}
</section>

{% endif %}

<style>
/* Research Grid */
.research-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.research-item {
  background: rgba(255, 255, 255, 0.05);
  padding: 2rem;
  border-radius: 15px;
  text-align: center;
  border: 1px solid rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
}

.research-item:hover {
  background: rgba(255, 255, 255, 0.1);
  transform: translateY(-5px);
  box-shadow: 0 10px 30px rgba(74, 158, 255, 0.2);
}

.research-icon {
  width: 60px;
  height: 60px;
  background: linear-gradient(45deg, #4a9eff, #00d4ff);
  border-radius: 50%;
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 0 auto 1rem;
  font-size: 1.5rem;
  color: white;
}

.research-item h3 {
  color: #4a9eff;
  margin-bottom: 1rem;
  font-size: 1.2rem;
}

.research-item p {
  color: #e6f3ff;
  font-size: 0.95rem;
  line-height: 1.5;
}

/* Training Grid */
.training-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin: 2rem 0;
}

.training-item {
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  overflow: hidden;
  border: 1px solid rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
}

.training-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 40px rgba(74, 158, 255, 0.3);
}

.training-header {
  background: linear-gradient(45deg, #4a9eff, #00d4ff);
  padding: 1.5rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.training-header h3 {
  color: white;
  margin: 0;
  font-size: 1.2rem;
}

.training-level {
  background: rgba(255, 255, 255, 0.2);
  padding: 0.3rem 0.8rem;
  border-radius: 15px;
  font-size: 0.8rem;
  color: white;
  font-weight: 600;
}

.training-details {
  padding: 1.5rem;
}

.training-details p {
  color: #e6f3ff;
  margin-bottom: 1rem;
  line-height: 1.6;
}

.training-cta {
  text-align: center;
  margin-top: 3rem;
  padding: 2rem;
  background: rgba(74, 158, 255, 0.1);
  border-radius: 15px;
  border: 1px solid rgba(74, 158, 255, 0.3);
}

.training-cta h3 {
  color: #4a9eff;
  margin-bottom: 1rem;
  font-size: 1.5rem;
}

.cta-button {
  display: inline-block;
  background: linear-gradient(45deg, #4a9eff, #00d4ff);
  color: white;
  padding: 1rem 2rem;
  border-radius: 25px;
  text-decoration: none;
  font-weight: 600;
  margin-top: 1rem;
  transition: all 0.3s ease;
}

.cta-button:hover {
  transform: translateY(-2px);
  box-shadow: 0 10px 30px rgba(74, 158, 255, 0.4);
  color: white;
  text-decoration: none;
}

/* Events Grid */
.events-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.event-item {
  background: rgba(255, 255, 255, 0.05);
  padding: 2rem;
  border-radius: 15px;
  border: 1px solid rgba(255, 255, 255, 0.1);
  display: flex;
  gap: 1.5rem;
  align-items: center;
  transition: all 0.3s ease;
}

.event-item:hover {
  background: rgba(255, 255, 255, 0.1);
  transform: translateY(-5px);
}

.event-date {
  background: linear-gradient(45deg, #4a9eff, #00d4ff);
  padding: 1rem;
  border-radius: 10px;
  text-align: center;
  min-width: 80px;
}

.event-date .month {
  display: block;
  color: white;
  font-size: 0.9rem;
  font-weight: 600;
}

.event-date .day {
  display: block;
  color: white;
  font-size: 1.5rem;
  font-weight: bold;
}

.event-details h3 {
  color: #4a9eff;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}

.event-details p {
  color: #e6f3ff;
  margin-bottom: 0.5rem;
  font-size: 0.95rem;
}

.event-type {
  background: rgba(74, 158, 255, 0.2);
  color: #4a9eff;
  padding: 0.3rem 0.8rem;
  border-radius: 12px;
  font-size: 0.8rem;
  font-weight: 600;
}

/* Partner descriptions */
.partner-description {
  font-size: 0.9rem;
  color: #b0c4de;
  margin-top: 0.5rem;
  line-height: 1.4;
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .research-grid,
  .training-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .events-grid {
    grid-template-columns: 1fr;
  }
  
  .event-item {
    flex-direction: column;
    text-align: center;
  }
  
  .training-header {
    flex-direction: column;
    gap: 1rem;
  }
}
</style>
