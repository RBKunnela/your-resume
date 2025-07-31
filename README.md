# Your-Resume: AI-Powered Professional Resume Template

Create an impressive, interactive professional resume with AI assistance - no coding skills required!

This template is designed to be easily customizable using AI tools like ChatGPT or Claude. You can create a professional resume with minimal effort by leveraging AI to fill in your personal information.

## How to Use This Template with AI

### Option 1: Ask AI to Fill in the Template

1. **Copy the template HTML file** (`index.html`) and send it to ChatGPT, Claude, or any other AI assistant.

2. **Share your photo** with the AI (if using a tool that accepts images like Claude or GPT-4 with Vision):
   - Upload your professional photo to the AI chat
   - Ask the AI to encode it as a base64 image or use the file URL in the template
   - Alternatively, tell the AI where you'll place the image file (e.g., "My photo will be named 'profile.jpg' in the same folder")

3. **Provide your resume information** in text form. You can structure it like this:

```
Please customize this resume template with my information:

Personal Info:
- Name: [Your Name]
- Title: [Your Professional Title]
- Email: [Your Email]
- Phone: [Your Phone Number]
- Location: [Your City, State/Country]

Skills:
- Skill 1 (Expert)
- Skill 2 (Advanced)
- Skill 3 (Intermediate)
- etc.

Experience:
1. [Job Title] at [Company Name] ([Start Date] - [End Date])
   - [Responsibility/Achievement]
   - [Responsibility/Achievement]
   - [Responsibility/Achievement]
   Skills used: [Relevant skills]

2. [Previous Job Title] at [Previous Company] ([Start Date] - [End Date])
   - [Responsibility/Achievement]
   - [Responsibility/Achievement]
   Skills used: [Relevant skills]

Education:
- [Degree] from [University/Institution] ([Year] - [Year])

Certifications:
- [Certification Name] ([Date])
- [Certification Name] ([Date])

Achievements:
- [Key Achievement 1]
- [Key Achievement 2]
```

3. **Ask the AI** to fill in the template with your information.

4. **Save the AI-generated HTML** file to your computer.

### Option 2: Edit the Template Directly

1. Open the `index.html` file in a text editor.
2. Replace all placeholder text with your information.
3. Replace the `profile-placeholder.jpg` with your own photo.

## Using Your Generated Resume

Once you have your customized resume, you can:

1. **Open it locally** in any web browser to view it.

2. **Generate a PDF** by clicking the "Download PDF" button on the resume page.

3. **Deploy it online** to share with potential employers:

### Deploying to Railway

1. Create a Railway account using this referral link: [Railway](https://railway.com?referralCode=bXRC89)

2. Upload your resume to GitHub:
   - Create a new GitHub repository
   - Upload your entire resume folder (index.html, profile photo, package.json, server.js, .gitignore)
   - Commit and push your changes

3. Deploy on Railway:
   - In Railway, click "New" button
   - Select "Deploy from GitHub repo"
   - Choose your resume repository
   - Railway will automatically detect the Express server configuration
   - Your app will be deployed in a few minutes

4. Your resume is now live online with a unique URL you can share with anyone!

> **Note**: This template includes all necessary files for Railway deployment. The Express server (server.js) will automatically serve your resume.

## Customization Tips

- **Photo**: You have several options for adding your photo:
  - Replace `profile-placeholder.jpg` with your own photo (keep the same filename)
  - Update the image path in the HTML if using a different filename
  - If working with AI, you can upload your photo directly to the AI and ask it to include it in the template
  - For Claude or GPT-4 with Vision, you can have the AI encode your photo as a base64 string directly in the HTML
- **Colors**: Modify the CSS variables to match your personal brand.
- **Sections**: Add or remove sections based on your needs.
- **Icons**: You can change the icons using Font Awesome classes.
- **Language**: Create your resume in any language by asking AI to translate the template:
  ```
  Please translate all text in this resume template to [YOUR LANGUAGE] while preserving 
  the HTML structure and styling. Keep technical terms and HTML/CSS/JavaScript code intact.
  ```

## Example AI Prompt

Here's an example prompt you can use with ChatGPT or Claude:

```
I have an HTML resume template. I'd like you to customize it with my personal information. Please update all placeholder text with my information while keeping the structure and styling intact.

[If you're sharing a photo] I'm also sharing my professional photo which I'd like you to use in the template. Please update the HTML to include my photo instead of the placeholder.

Here's my information:

[PASTE YOUR RESUME INFORMATION HERE]

Here's the template:

[PASTE THE ENTIRE index.html CONTENT HERE]
```

## Need Help?

If you need assistance, you can:
1. Ask an AI assistant for help with specific parts of the template
2. Refer to the original template at [GitHub Repository](https://github.com/RBKunnela/your-resume)

---

## See It In Action

Want to see what your resume could look like? Check out the creator's resume built with this template:

🔗 [View Example Resume](https://renata-resume-production.up.railway.app/)

Note: The example resume is a separate deployment. Your resume will be unique to you and your information!

## Features

- 🤖 **AI Integration** - Just paste into ChatGPT or Claude
- 📱 **Responsive Design** - Looks great on all devices
- 📄 **PDF Download** - One-click PDF generation
- 🔄 **Interactive Elements** - Engage potential employers
- 🚀 **Easy Deployment** - Ready for Railway hosting
- 💼 **Professional Design** - Stand out from other candidates
- 🌐 **Multilingual Support** - Create in any language with AI assistance

## Multilingual Resume Creation

This template can be easily translated to any language using AI. Simply ask the AI assistant to translate the template while maintaining its structure and functionality.

### Example AI Prompt for Translation:

```
Please translate this resume template to [YOUR LANGUAGE, e.g., Spanish, French, German, etc.]. 
Maintain all HTML structure, CSS styling, and JavaScript functionality. 
Only translate the visible text content that would appear on the webpage.

For example:
- Translate "Your Name" to the equivalent in the target language
- Translate section titles like "Professional Experience" and "Education"
- Translate button text like "Download PDF" and "Email Me"
- Do NOT translate HTML tags, class names, or JavaScript code
```

This allows you to create your resume in your native language or target your resume for specific regional job markets.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

Template created by Renata Baldissara-Kunnela, © 2023-2025. Customizable for personal use.