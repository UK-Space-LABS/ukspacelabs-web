---
layout: default
title: Meet the Team
subtitle: The People Behind UK Space LABS

core_members:
  - name: "(Replace)"
    title: "Chair & Human Spaceflight Specialist"
    role: "Strategic Leadership"
    bio: "Leading expert in human spaceflight physiology with 15+ years experience in space medicine research and astronaut training protocols."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Research Director"
    role: "Scientific Oversight"
    bio: "Renowned biomedical researcher specializing in microgravity effects on human physiology and space-based medical countermeasures."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Education Coordinator"
    role: "Academic Outreach"
    bio: "Expert in space life sciences education, developing curricula for universities and training programs for space medicine professionals."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Industry Relations Manager"
    role: "Commercial Partnerships"
    bio: "Bridges academia and industry, fostering collaborations between research institutions and commercial space companies."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "International Coordinator"
    role: "Global Partnerships"
    bio: "Facilitates international collaborations and represents UK Space LABS at global space medicine conferences and initiatives."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Technology Integration Lead"
    role: "Innovation & Tech"
    bio: "Specializes in integrating emerging technologies into space biomedical research and developing next-generation space health solutions."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Public Engagement Officer"
    role: "Community Outreach"
    bio: "Champions public understanding of space life sciences through media engagement, school visits, and community programs."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Data Science Coordinator"
    role: "Analytics & Research"
    bio: "Leads data analysis initiatives for space biomedical research, developing AI/ML solutions for space health monitoring."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Ethics & Policy Advisor"
    role: "Regulatory Affairs"
    bio: "Ensures ethical standards in space biomedical research and advises on policy matters affecting human spaceflight."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Operations Manager"
    role: "Organizational Development"
    bio: "Oversees day-to-day operations, strategic planning, and organizational development for sustainable growth."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"

external_contacts:
  - name: "(Replace)"
    title: "UK Space Agency Liaison"
    organization: "UK Space Agency"
    role: "Government Relations"
    bio: "Primary liaison with UKSA, facilitating policy discussions and funding opportunities for space life sciences research."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "RAeS Space Medicine Group Lead"
    organization: "Royal Aeronautical Society"
    role: "Professional Standards"
    bio: "Leads the space medicine special interest group, setting professional standards and certification requirements."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "AsMA International Representative"
    organization: "Aerospace Medical Association"
    role: "International Standards"
    bio: "Represents UK interests in international aerospace medicine standards and global space health initiatives."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "Blue Abyss Research Director"
    organization: "Blue Abyss Ltd"
    role: "Commercial Research"
    bio: "Oversees research collaborations and commercial applications of space life sciences in underwater analog environments."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "ESA Human Spaceflight Advisor"
    organization: "European Space Agency"
    role: "European Collaboration"
    bio: "Coordinates European space medicine initiatives and facilitates UK participation in ESA human spaceflight programs."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"
  - name: "(Replace)"
    title: "NASA Life Sciences Coordinator"
    organization: "NASA"
    role: "US Collaboration"
    bio: "Manages collaborative research programs between UK institutions and NASA's space life sciences division."
    image: "images/team/UK_Space_LABS_Team_profile_placeholder.png"

executive_committee:
  - name: "(Replace)"
    role: "Chair"
  - name: "(Replace)"
    role: "Vice Chair"
  - name: "(Replace)"
    role: "Secretary"
  - name: "(Replace)"
    role: "Treasurer"
  - name: "(Replace)"
    role: "International Relations"
  - name: "(Replace)"
    role: "Technical Affairs"
---

<section class="team-intro">
  <h2>Meet Our Team</h2>
  <p class="team-description">
    UK Space LABS brings together a diverse team of seasoned experts, early career professionals and students from across the space life sciences community and aligned sectors. Our team combines decades of experience in space medicine, biomedical research, education, and industry collaboration to advance the field of space biomedicine in the UK and internationally.
  </p>
</section>

<section class="core-members-section">
  <h2>Core Members</h2>
  <div class="team-grid">
    {% for member in page.core_members %}
    <div class="team-member-card">
      <div class="member-image">
        <img src="{{ member.image | relative_url }}" alt="{{ member.name }}" class="profile-img">
      </div>
      <div class="member-info">
        <h3 class="member-name">{{ member.name }}</h3>
        <h4 class="member-title">{{ member.title }}</h4>
        <p class="member-role">{{ member.role }}</p>
        <p class="member-bio">{{ member.bio }}</p>
      </div>
    </div>
    {% endfor %}
  </div>
</section>

<section class="external-contacts-section">
  <h2>External Agency Point of Contacts</h2>
  <div class="team-grid">
    {% for contact in page.external_contacts %}
    <div class="team-member-card external-contact">
      <div class="member-image">
        <img src="{{ contact.image | relative_url }}" alt="{{ contact.name }}" class="profile-img">
      </div>
      <div class="member-info">
        <h3 class="member-name">{{ contact.name }}</h3>
        <h4 class="member-title">{{ contact.title }}</h4>
        <p class="member-organization">{{ contact.organization }}</p>
        <p class="member-role">{{ contact.role }}</p>
        <p class="member-bio">{{ contact.bio }}</p>
      </div>
    </div>
    {% endfor %}
  </div>
</section>

<section class="executive-committee-section">
  <h2>Executive Committee</h2>
  <div class="executive-grid">
    {% for member in page.executive_committee %}
    <div class="executive-member">
      <h4 class="exec-name">{{ member.name }}</h4>
      <p class="exec-role">{{ member.role }}</p>
    </div>
    {% endfor %}
  </div>
</section>

<section class="team-message">
  <div class="message-container">
    <img src="{{ 'images/we_are_here_for_now.png' | relative_url }}" alt="Here we are, at least for now" class="team-message-img">
  </div>
</section>

<style>
.team-intro {
  text-align: center;
  margin-bottom: 3rem;
}

.team-description {
  font-size: 1.1rem;
  line-height: 1.7;
  color: #e6f3ff;
  margin: 1.5rem 0;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.core-members-section h2,
.external-contacts-section h2,
..executive-committee-section h2 {
  color: #def3fb !important; /* Brighter */
  text-shadow: 0 0 10px rgba(74, 158, 255, 0.5);
  font-size: 2rem;
  margin: 4rem 0;
}

.team-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
}

.team-member-card {
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  padding: 2rem;
  border: 1px solid rgba(255, 255, 255, 0.1);
  transition: all 0.3s ease;
  text-align: center;
}

.team-member-card:hover {
  background: rgba(255, 255, 255, 0.1);
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(74, 158, 255, 0.2);
}

.external-contact {
  border-left: 4px solid #00d4ff;
}

.member-image {
  margin-bottom: 1.5rem;
}

.profile-img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  border: 3px solid rgba(74, 158, 255, 0.5);
  background: rgba(255, 255, 255, 0.1);
}

.member-name {
  color: #4a9eff;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}

.member-title {
  color: #87ceeb;
  font-style: italic;
  margin-bottom: 0.5rem;
  font-size: 1rem;
}

.member-organization {
  color: #00d4ff;
  font-weight: 600;
  margin-bottom: 0.5rem;
  font-size: 0.9rem;
}

.member-role {
  color: #b0c4de;
  font-size: 0.9rem;
  margin-bottom: 1rem;
  padding: 0.3rem 0.8rem;
  background: rgba(74, 158, 255, 0.2);
  border-radius: 12px;
  display: inline-block;
}

.member-bio {
  color: #e6f3ff;
  font-size: 0.9rem;
  line-height: 1.5;
}

.executive-committee-section {
  margin: 4rem 0;
  text-align: center;
}

.executive-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  margin-top: 2rem;
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
}

.executive-member {
  background: rgba(74, 158, 255, 0.1);
  padding: 1.5rem;
  border-radius: 10px;
  border: 1px solid rgba(74, 158, 255, 0.3);
}

.exec-name {
  color: #4a9eff;
  margin-bottom: 0.5rem;
  font-size: 1rem;
}

.exec-role {
  color: #87ceeb;
  font-style: italic;
  font-size: 0.9rem;
}

.team-message {
  margin: 4rem 0;
  text-align: center;
}

.message-container {
  max-width: 600px;
  margin: 0 auto;
  padding: 2rem;
  background: rgba(255, 255, 255, 0.05);
  border-radius: 15px;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.team-message-img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
}

/* Responsive adjustments */
@media (max-width: 768px) {
  .team-grid {
    grid-template-columns: 1fr;
    gap: 1.5rem;
  }
  
  .team-member-card {
    padding: 1.5rem;
  }
  
  .executive-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}

@media (max-width: 480px) {
  .executive-grid {
    grid-template-columns: 1fr;
  }
  
  .message-container {
    padding: 1rem;
  }
}

</style>
