<svelte:head>
  <title>Our Projects & Ideas | Palanhaar Solutions</title>
  <meta name="description" content="Explore Palanhaar Solutions' key projects including Indian Railways Super App, iDukaan, and GoAnubhavBharat. Discover our journey in transport, tourism, and digital innovation.">
  <meta name="keywords" content="Palanhaar Solutions, Indian Railways Super App, iDukaan, GoAnubhavBharat, Digital India Projects, Railway App, Tourism App, Travel Planner, Local Shops Platform, Cultural Discovery, Transport Innovation">
  <meta property="og:title" content="Our Projects & Ideas | Palanhaar Solutions">
  <meta property="og:description" content="Discover our work in transport tech and cultural tourism—from Indian Railways Super App to GoAnubhavBharat.">
  <!-- <meta property="og:image" content="https://yourdomain.com/static/project-thumbnail.jpg">
  <meta property="og:url" content="https://yourdomain.com/projects"> -->
  <meta property="og:type" content="website">
</svelte:head>

<section class="ideas-section min-h-screen">
  <h1>Our Projects & Ideas</h1>

  <div class="project-card">
    <h2>Indian Railways Super App</h2>
    <p>
      A comprehensive platform envisioned to unify all Indian Railways services in a single app. Though now concluded, our proposal laid the foundation for CRIS to adopt the idea.
    </p>
    <div class="links">
      <a href="#">Proposal</a>
      <a href="#">Presentation</a>
      <a href="#">RTI Reply</a>
      <a href="#">Demo Video</a>
    </div>
    <span class="status closed">Status: Closed</span>
    <div class="hashtags">#IndianRailways #UnifiedApp #PublicInnovation #TransportTech #GovTech</div>
  </div>

  <div class="project-card">
    <h2>iDukaan</h2>
    <p>
      An initiative to enhance the visibility of verified station vendors without requiring online orders. This initiative, part of the Super App, is now concluded.
    </p>
    <div class="links">
      <a href="#">Proposal</a>
      <a href="#">Presentation</a>
      <a href="#">Demo Video</a>
    </div>
    <span class="status closed">Status: Closed</span>
    <div class="hashtags">#iDukaan #VendorSupport #RailwayShops #DigitalInclusion #SmartRailway</div>
  </div>

  <div class="project-card">
    <h2>GoAnubhavBharat</h2>
    <p>
      A cultural and travel discovery platform built to help users explore India’s diverse beauty and traditions, with verified information, guides, and planning tools.
    </p>
    <div class="links">
      <a href="https://goanubhavbharat.com" target="_blank">Website</a>
    </div>
    <span class="status active">Status: Active</span>
    <div class="hashtags">#GoAnubhavBharat #IncredibleIndia #DigitalTravel #BharatDarshan #LocalExploration</div>
  </div>
</section>

<style>
.ideas-section {
  max-width: 860px;
  margin: 0 auto;
  padding: 2rem 1rem;
  background: linear-gradient(to bottom right, #fafafa, #fefefe);
  min-height: 100vh;
}
.ideas-section h1 {
  text-align: center;
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 2rem;
  color: #1e293b;
}
.project-card {
  background: #ffffff;
  border: 1px solid #e2e8f0;
  border-radius: 10px;
  padding: 1.5rem;
  margin-bottom: 1.5rem;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.02);
  transition: box-shadow 0.2s;
}
.project-card:hover {
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.05);
}
.project-card h2 {
  font-size: 1.2rem;
  font-weight: 600;
  color: #334155;
  margin-bottom: 0.6rem;
}
.project-card p {
  font-size: 0.98rem;
  color: #4b5563;
  line-height: 1.6;
  margin-bottom: 1rem;
}
.links {
  display: flex;
  flex-wrap: wrap;
  gap: 1rem;
  margin-bottom: 0.8rem;
}
.links a {
  color: #1d4ed8;
  text-decoration: none;
  font-weight: 500;
  font-size: 0.92rem;
}
.links a:hover {
  text-decoration: underline;
}
.status {
  display: inline-block;
  font-size: 0.8rem;
  font-weight: 500;
  padding: 0.25rem 0.6rem;
  border-radius: 999px;
  margin-top: 0.2rem;
}
.status.closed {
  background: #fee2e2;
  color: #b91c1c;
}
.status.active {
  background: #dcfce7;
  color: #15803d;
}
.hashtags {
  margin-top: 0.6rem;
  font-size: 0.85rem;
  color: #6b7280;
}
</style>
