# Styles.css  
  
/* Reset and Base Styles */  
* {  
  margin: 0;  
  padding: 0;  
  box-sizing: border-box;  
}  
  
body {  
  font-family: 'Inter', sans-serif;  
  font-size: 16px;  
  line-height: 1.6;  
  color: #333333;  
  background: #F5F5F5;  
}  
  
.container {  
  max-width: 1200px;  
  margin: 0 auto;  
  padding: 0 16px;  
}  
  
.section {  
  padding: 64px 0;  
}  
  
h1, h2, h3 {  
  color: #001F3F;  
}  
  
h1 {  
  font-size: 48px;  
  margin-bottom: 16px;  
}  
  
h2 {  
  font-size: 32px;  
  margin-bottom: 32px;  
}  
  
.btn {  
  display: inline-block;  
  padding: 8px 16px;  
  background: #7FDBFF;  
  color: #001F3F;  
  text-decoration: none;  
  border-radius: 4px;  
  margin: 8px 8px 0 0;  
  transition: background 0.3s;  
}  
  
.btn:hover {  
  background: #001F3F;  
  color: #F5F5F5;  
}  
  
/* Hero Section */  
.hero {  
  background: #001F3F;  
  color: #F5F5F5;  
  text-align: center;  
  padding: 96px 0;  
}  
  
.hero-img {  
  width: 120px;  
  height: 120px;  
  border-radius: 50%;  
  object-fit: cover;  
  margin-bottom: 16px;  
}  
  
.tagline {  
  font-size: 20px;  
  margin-bottom: 24px;  
}  
  
.hero-links {  
  display: flex;  
  justify-content: center;  
  gap: 16px;  
}  
  
/* Skills Section */  
.skills-grid {  
  display: grid;  
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));  
  gap: 16px;  
}  
  
.skill-item {  
  background: #FFFFFF;  
  padding: 16px;  
  text-align: center;  
  border-radius: 4px;  
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);  
}  
  
/* Projects Section */  
.projects-grid {  
  display: grid;  
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));  
  gap: 32px;  
}  
  
.project-card {  
  background: #FFFFFF;  
  padding: 16px;  
  border-radius: 4px;  
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);  
  transition: transform 0.3s;  
}  
  
.project-card:hover {  
  transform: translateY(-4px);  
}  
  
.project-img {  
  width: 100%;  
  height: 200px;  
  object-fit: cover;  
  border-radius: 4px;  
  margin-bottom: 16px;  
}  
  
/* Experience Section */  
.experience-item {  
  margin-bottom: 32px;  
}  
  
.experience-item ul {  
  list-style: disc;  
  margin-left: 24px;  
}  
  
/* Contact Section */  
form {  
  display: flex;  
  flex-direction: column;  
  max-width: 600px;  
  margin: 0 auto;  
}  
  
label {  
  margin: 8px 0 4px;  
}  
  
input, textarea {  
  padding: 8px;  
  border: 1px solid #001F3F;  
  border-radius: 4px;  
  margin-bottom: 16px;  
}  
  
textarea {  
  resize: vertical;  
  min-height: 100px;  
}  
  
footer {  
  text-align: center;  
  padding: 32px 0;  
  background: #001F3F;  
  color: #F5F5F5;  
}  
  
/* Responsive Design */  
@media (max-width: 768px) {  
  h1 { font-size: 36px; }  
  h2 { font-size: 24px; }  
  .hero { padding: 64px 0; }  
  .section { padding: 32px 0; }  
}  
