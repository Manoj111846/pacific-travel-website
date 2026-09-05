<img width="1896" height="977" alt="image" src="https://github.com/user-attachments/assets/cbdb7f23-48ca-4843-9bd5-e73984cf9e5e" /><img width="1896" height="977" alt="image" src="https://github.com/user-attachments/assets/e0204ac7-3293-4977-8937-da620bb9d52a" /># 🌴 Pacific Travel Website

> **A static travel agency website deployed on Amazon S3 and maintained with GitHub.**

![Pacific Travel Website](screenshots/01-live-website.png)

## 🌐 Live Demo

**AWS S3 Static Website**

http://manoj-s3-static-website-2026.s3-website-us-east-1.amazonaws.com

## 🐙 Source Code

**GitHub Repository:**  
https://github.com/Manoj111846/pacific-travel-website

---

## 📖 About the Project

**Pacific Travel** is a static travel agency website created to provide a clean and attractive interface for discovering destinations, hotels, travel blogs, and contact information.

The project demonstrates a simple real-world **Cloud + Web Development + Git workflow**:

```text
Build Website → Test Locally → Git → GitHub → Amazon S3 → Live Website
```

---

## ✨ Key Features

- 🏠 Travel-focused homepage
- 🌍 Destination section
- 🏨 Hotel section
- 📝 Travel blog
- 📞 Contact page
- 🔎 Search interface
- 📱 Responsive web design
- 🎨 Modern travel-themed UI
- ☁️ Amazon S3 static website hosting
- 🐙 GitHub source-code management

---

## 🛠️ Technology Stack

| Technology | Role |
|---|---|
| **HTML5** | Page structure |
| **CSS3** | Styling and layout |
| **JavaScript** | Interactive functionality |
| **SCSS** | CSS source development |
| **Git** | Version control |
| **GitHub** | Code hosting |
| **Amazon S3** | Cloud storage & static website hosting |

---

## 📂 Project Structure

```text
pacific-travel-website/
│
├── css/
├── fonts/
├── images/
├── js/
├── scss/
│
├── about.html
├── blog.html
├── blog-single.html
├── contact.html
├── destination.html
├── hotel.html
├── index.html
├── main.html
│
├── prepros-6.config
└── README.md
```

---

# ☁️ AWS S3 Deployment

The website is deployed using **Amazon S3 Static Website Hosting**.

### S3 Bucket

```text
manoj-s3-static-website-2026
```

### Deployment Process

1. Create an S3 bucket.
2. Upload the website files and folders.
3. Enable Static Website Hosting.
4. Set `index.html` as the index document.
5. Configure the required public-access/bucket policy settings.
6. Open the S3 website endpoint.
7. Verify the website in a browser.

### S3 Website Endpoint

```text
http://manoj-s3-static-website-2026.s3-website-us-east-1.amazonaws.com
```

---

# 🐙 GitHub Deployment Workflow

The project was initialized and pushed to GitHub using Git.

```bash
git init
git add .
git commit -m "Initial upload of Pacific Travel website"
git branch -M main
git remote add origin https://github.com/Manoj111846/pacific-travel-website.git
git push -u origin main
```

For future updates:

```bash
git add .
git commit -m "Update Pacific Travel website"
git push
```

---

# 📸 Project Screenshots

## 1. Live Pacific Travel Website

The final website is successfully displayed through the Amazon S3 website endpoint.

![Uploading image.png…]()





---

## 2. GitHub Repository

The project source files are available in the GitHub repository.

![GitHub Repository](screenshots/02-github-repository-files.png)

---

## 3. Git Push Successfully Completed

The local project was successfully pushed to the `main` branch.

![Git Push Success](screenshots/03-git-push-success.png)

---

## 4. Amazon S3 Bucket

The S3 bucket used for hosting the website is visible in the AWS console.

![S3 Bucket](screenshots/04-s3-bucket.png)

---

## 5. Website Files in S3

The website HTML files and supporting assets were uploaded to the S3 bucket.

![S3 Objects](screenshots/05-s3-website-objects.png)

---

## 6. Static Website Hosting Enabled

Amazon S3 Static Website Hosting is enabled and the website endpoint is displayed.

![S3 Static Website Hosting](screenshots/06-s3-static-website-hosting.png)

---

## 7. Public Access Configuration

The S3 bucket's public-access configuration was reviewed for website hosting.

![S3 Public Access](screenshots/07-s3-public-access-setting.png)

---

## 8. Uploaded Website Folders

The CSS, fonts, images, JavaScript, and SCSS folders are present in the S3 bucket.

![S3 Uploaded Folders](screenshots/08-s3-uploaded-folders.png)

---

# 🎯 Learning Outcomes

This project provided hands-on experience with:

- Static website development
- HTML, CSS and JavaScript
- SCSS
- Git and GitHub
- Git repositories and commits
- Git branches and remote repositories
- Amazon S3 buckets
- S3 object storage
- Static website hosting
- Public access configuration
- Cloud deployment
- Basic DevOps workflow

---

# 🔄 Architecture / Workflow

```text
                ┌─────────────────────┐
                │  Pacific Travel     │
                │      Website        │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │ HTML / CSS / JS     │
                │ Images / Fonts      │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │       Git           │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │      GitHub         │
                │  Source Repository  │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    Amazon S3        │
                │ Static Web Hosting  │
                └──────────┬──────────┘
                           │
                           ▼
                ┌─────────────────────┐
                │    Live Website     │
                └─────────────────────┘
```

---

# 🚀 Future Enhancements

The project can be extended with:

- Online hotel booking
- User authentication
- Destination search
- Database integration
- Contact form backend
- Payment gateway
- Weather API
- Google Maps integration
- AWS CloudFront
- HTTPS with CloudFront
- Custom domain
- GitHub Actions CI/CD
- Automated S3 deployment

---

# 🔐 Security

Sensitive information should never be committed to GitHub or uploaded to a public S3 bucket.

Do not upload:

```text
AWS Access Keys
AWS Secret Keys
Passwords
.env files
.pem files
Private credentials
```

---

# 👨‍💻 Author

**Manoj**

GitHub:  
https://github.com/Manoj111846

---

# 📊 Project Status

| Component | Status |
|---|---|
| Website Development | ✅ Complete |
| Local Testing | ✅ Complete |
| Git Repository | ✅ Complete |
| GitHub Upload | ✅ Complete |
| S3 Bucket | ✅ Complete |
| Website Files Uploaded | ✅ Complete |
| Static Website Hosting | ✅ Enabled |
| Live Website | ✅ Deployed |

---

## ⭐ Conclusion

The **Pacific Travel Website** demonstrates how a static website can be developed, version-controlled with Git/GitHub, and deployed to the cloud using **Amazon S3 Static Website Hosting**.

> **Web Development + Git/GitHub + AWS Cloud + Deployment = Practical Cloud Project 🚀**
