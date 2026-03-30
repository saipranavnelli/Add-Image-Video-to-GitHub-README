# 📸 How To Add Images & 🎥 Video To GitHub README

## 📖 Introduction

In this guide, you'll learn how to add both images and videos to a GitHub README file.

Adding visuals like screenshots and demo videos makes your project more attractive and easy to understand.

---

## 🧠 What You Will Learn

- Add images to README
- Add video (best possible way)
- Use GitHub Permalink (recommended)
- Best practices

---

# 📸 Screenshots

### 🟢 EC2 Instance Setup

![EC2 Setup](https://raw.githubusercontent.com/saipranavnelli/ec2-nginx-status-demo/c27df3cbc943ffcbbb3a47dc85272b596c914b9b/Screenshot%20From%202026-03-25%2017-14-53.png)

---

### 🔐 Security Group Configuration

![Security Group](https://raw.githubusercontent.com/saipranavnelli/ec2-nginx-status-demo/c27df3cbc943ffcbbb3a47dc85272b596c914b9b/Screenshot%20From%202026-03-25%2017-14-30.png)

---

# 🎥 Demo Video

👉 Click below to watch the demo video:

[![Watch Demo](https://raw.githubusercontent.com/saipranavnelli/ec2-nginx-status-demo/c27df3cbc943ffcbbb3a47dc85272b596c914b9b/Screenshot%20From%202026-03-25%2017-14-53.png)](https://raw.githubusercontent.com/saipranavnelli/ec2-nginx-status-demo/ddd3237694189681d5bdc968118f730fcc953556/ec2-nginx-demo.mp4)

---

# 🔧 Steps To Add Images

1. Upload image to GitHub  
2. Open the image file  
3. Click on **3 dots (⋯) on top right**  
4. Click **Copy permalink**  
5. Convert link:
   - Replace `github.com` → `raw.githubusercontent.com`
   - Remove `/blob`

Example:

❌ Wrong:
https://github.com/user/repo/blob/main/image.png  

✅ Correct:
https://raw.githubusercontent.com/user/repo/main/image.png  

6. Add in README:

```md
![Image](image_url)
