# Cloud Computing Project: Static Website Hosting with Netlify 🌐

A simple website demonstrating cloud computing concepts (IaaS, PaaS, SaaS) hosted on Netlify as part of a cloud infrastructure project.

🔗 **Live Website:** [Cloud Computing Seminar Project](https://cloud-computing-seminar-project.netlify.app)

## 🚀 Features
- Basic introduction to cloud computing
- Explanation of three fundamental cloud service models:
  - Infrastructure as a Service (IaaS)
  - Platform as a Service (PaaS)
  - Software as a Service (SaaS)
- Responsive design
- Minimalist UI

## 🛠️ Technologies Used
- HTML5
- [Netlify](https://www.netlify.com/) (PaaS Cloud Platform)

## 📋 Prerequisites
- GitHub account
- Netlify account (free tier)
- Basic understanding of HTML
- Code editor (VS Code recommended)

## 🚨 Deployment Steps

### Connecting to Netlify
1. **Log in to Netlify**  
   Visit [app.netlify.com](https://app.netlify.com) and sign in with GitHub.

2. **Choose Deployment Method**  
   - **Drag & Drop**:  
     Go to the "Sites" tab → Drag your `index.html` file into Netlify's deployment zone.  
   - **GitHub Integration (Recommended)**:  
     Click "Import an existing project" → Authorize Netlify → Select [your repository](https://github.com/RajathPatilKulkarni/Cloud-Computing-Seminar-Website.git).

3. **Trigger Deployment**  
   Netlify will automatically:
   - Detect `index.html`
   - Generate a unique URL (e.g., `your-site.netlify.app`)
   - Enable HTTPS
   - Deploy via global CDN

## 💻 Running Locally
1. **Serve Locally**  
   ```bash
   python3 -m http.server 8000
   ```

## 🚀 Direct File Access

You can open `index.html` directly in a browser to view the project.

## ✨ Customization

### 📂 File Structure
```
index.html
```

### 🛠 Editing Guide
#### 🔹 Update Content
Modify the text in `index.html` as needed.

## 🚀 Run HTML

### ☁️ Auto-Deploy with Netlify
Netlify automatically updates the project when you push changes to GitHub.

```bash
git add .
git commit -m "Update content"
git push origin main
```

## ☁️ Cloud Models in Action (PaaS)

| Feature              | Implementation Details                  |
|---------------------|-------------------------------------|
| **Infrastructure (IaaS)** | Netlify manages servers and networking |
| **SSL Certificates**     | Auto-provisioned via Let's Encrypt  |
| **Global CDN**         | Content cached in 21+ regions      |
| **CI/CD Pipeline**     | Instant deployments on Git push    |

## 📄 License
This project is licensed under the [MIT License](LICENSE).

## 👤 Author
**Rajath Patil Kulkarni**  
- 🔗 [GitHub](https://github.com/RajathPatilKulkarni-06)  
- 📂 [Project Repository](https://github.com/RajathPatilKulkarni/Cloud-Computing-Seminar-Website.git)  
- 🌐 [Live Project](https://cloud-computing-seminar-project.netlify.app)

## 🙏 Acknowledgments
- **NIST SP 800-145** cloud standards



