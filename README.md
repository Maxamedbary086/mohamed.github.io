# mohamed.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Waiye District Hospital</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background-color: #004d40;
      color: white;
      padding: 20px 10%;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      background-color: #00796b;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
      padding: 8px 15px;
      border-radius: 4px;
    }
    nav a:hover {
      background-color: #004d40;
    }
    main {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }
    section {
      margin-bottom: 40px;
    }
    h2 {
      color: #00796b;
      border-bottom: 3px solid #004d40;
      padding-bottom: 5px;
    }
    .hero-image {
      width: 100%;
      max-height: 350px;
      object-fit: cover;
      border-radius: 8px;
      margin-bottom: 20px;
    }
    .quick-links {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin: 20px 0;
      flex-wrap: wrap;
    }
    .quick-links a {
      background-color: #004d40;
      color: white;
      padding: 15px 25px;
      border-radius: 6px;
      text-decoration: none;
      font-size: 1.1em;
      transition: background-color 0.3s ease;
    }
    .quick-links a:hover {
      background-color: #00796b;
    }
    .partners-banner {
      background-color: #e0f2f1;
      padding: 15px 10%;
      display: flex;
      overflow-x: auto;
      gap: 30px;
      align-items: center;
      border-top: 2px solid #004d40;
      border-bottom: 2px solid #004d40;
    }
    .partners-banner img {
      height: 50px;
      object-fit: contain;
    }
    footer {
      background-color: #004d40;
      color: white;
      text-align: center;
      padding: 15px 10%;
      font-size: 0.9em;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    th, td {
      border: 1px solid #ccc;
      padding: 8px;
      text-align: left;
    }
    th {
      background-color: #00796b;
      color: white;
    }
    @media (max-width: 600px) {
      nav {
        flex-direction: column;
      }
      .quick-links {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Waiye District Hospital</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#services">Our Services</a>
    <a href="#health-info">Health Info</a>
    <a href="#partners">Partners</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <!-- Home Section -->
    <section id="home">
      <img src="https://example.com/waiye-hospital-main-building.jpg" alt="Waiye District Hospital" class="hero-image" />
      <p><strong>Welcome to Waiye District Hospital,</strong> committed to providing essential healthcare services to the Karkaar region community with support from local and international partners.</p>
      <div class="quick-links">
        <a href="#services">Our Services</a>
        <a href="#health-info">Patient Information</a>
        <a href="#contact">Find Us / Contact</a>
      </div>
    </section>

    <!-- About Us Section -->
    <section id="about">
      <h2>About Us</h2>
      <h3>Our History & Mission</h3>
      <p>Waiye District Hospital serves the Bari region of Puntland, Somalia, providing comprehensive healthcare in a resource-limited setting. Our mission is to improve community health through quality medical services, public health education, and strong partnerships.</p>

      <h3>Our Facility</h3>
      <p>The hospital complex consists of several single-story buildings with dedicated departments including emergency, maternity, TB center, laboratory, and pharmacy. Our grounds are secured and equipped with essential medical equipment, including oxygen concentrators, ultrasound machines, and solar-powered backup systems.</p>

      <h3>Our Projects</h3>
      <ul>
        <li>Community Health and Nutrition CHANGE Project (2016-2021) - Supported by Save the Children and UK aid</li>
        <li>Solar Electrification for Health Centre - Funded by the European Commission and ADRA UK</li>
      </ul>
    </section>

    <!-- Our Services Section -->
    <section id="services">
      <h2>Our Services</h2>

      <h3>Emergency Services (Gargaarka Degdega)</h3>
      <p>24/7 emergency care to address urgent medical needs.</p>

      <h3>Maternal & Child Health</h3>
      <ul>
        <li><strong>Delivery Room (Qolka Dhalmada):</strong> Comprehensive maternity and delivery services.</li>
        <li><strong>Reproductive Health (Caafimaadka Taranka):</strong> Antenatal Care (ANC), Postnatal Care (PNC), and Family Planning (FPPAC).</li>
        <li><strong>Immunizations (Qolka Talaalka):</strong> Vaccinations including polio (IPV) and other essential immunizations.</li>
      </ul>

      <h3>Integrated TB Center</h3>
      <p>Dedicated diagnosis and treatment for tuberculosis patients.</p>

      <h3>Inpatient Care</h3>
      <ul>
        <li>Internal Medicine Ward</li>
        <li>General Ward (Bukaan Jif)</li>
      </ul>

      <h3>Outpatient Department (Bukaan Socod)</h3>
      <p>Routine consultations and follow-up care.</p>

      <h3>Laboratory (Sheybaar)</h3>
      <p>Diagnostic testing including hematology analysis.</p>

      <h3>Pharmacy (Daawada)</h3>
      <p>On-site pharmacy providing essential medications.</p>

      <h3>Medical Imaging</h3>
      <p>Ultrasound diagnostics available with portable equipment.</p>
    </section>

    <!-- Health Information Section -->
    <section id="health-info">
      <h2>Health Information & Resources</h2>

      <h3>Maternal and Child Health</h3>
      <p>Guidance on breastfeeding, newborn care, and the "Helping Babies Breathe" initiative.</p>

      <h3>Nutrition</h3>
      <p>Information from the World Food Programme on nutrition assistance and complementary feeding.</p>

      <h3>Disease Prevention</h3>
      <ul>
        <li>COVID-19 prevention: hand washing, mask-wearing, social distancing, vaccination.</li>
        <li>Hand hygiene: "Your 5 Moments for Hand Hygiene" campaign.</li>
        <li>Tuberculosis awareness and screening.</li>
      </ul>

      <h3>Sexual and Reproductive Health</h3>
      <p>Educational materials on family planning and sexual violence consequences.</p>
    </section>

    <!-- Partners Section -->
    <section id="partners">
      <h2>Our Partners</h2>
      <p>We gratefully acknowledge the support of our partners:</p>
      <div class="partners-banner" aria-label="Partner logos">
        <img src="https://example.com/logos/who.png" alt="World Health Organization" />
        <img src="https://example.com/logos/unicef.png" alt="UNICEF" />
        <img src="https://example.com/logos/wfp.png" alt="World Food Programme" />
        <img src="https://example.com/logos/usaid.png" alt="USAID" />
        <img src="https://example.com/logos/uk-aid.png" alt="UK aid" />
        <img src="https://example.com/logos/save-the-children.png" alt="Save the Children" />
        <img src="https://example.com/logos/world-vision.png" alt="World Vision" />
        <img src="https://example.com/logos/adra.png" alt="ADRA Somalia" />
        <img src="https://example.com/logos/gavi.png" alt="Gavi, the Vaccine Alliance" />
        <img src="https://example.com/logos/puntland-health.png" alt="Puntland Ministry of Health" />
      </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
      <h2>Contact Us</h2>
      <p><strong>Address:</strong> Waiye District Hospital, Bari Region, Puntland, Somalia</p>
      <p><strong>Phone:</strong> +252-XXX-XXXXXX</p>
      <p><strong>Operating Hours:</strong> Emergency 24/7, Outpatient 8:00 AM - 5:00 PM</p>
      <h3>Find Us</h3>
      <iframe
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3832.1234567890123!2d49.123456!3d10.123456!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x123456789abcdef%3A0xabcdef1234567890!2sWaiye%20District%20Hospital!5e0!3m2!1sen!2sso!4v1234567890"
        width="100%"
        height="300"
        style="border:0;"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        title="Waiye District Hospital Location"
      ></iframe>
    </section>
  </main>

  <footer>
    <p>© 2025 Waiye District Hospital. All rights reserved.</p>
  </footer>
</body>
</html>
