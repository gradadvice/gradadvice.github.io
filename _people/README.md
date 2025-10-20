# Adding Your Profile to the People Directory

Thank you for your interest in adding your profile to the PhD Advice Hub People Directory!

## How to Add Your Profile

1. Fork this repository
2. Create a new file in the `_people` directory
3. Name your file using lowercase letters and hyphens (e.g., `firstname-lastname.md`)
4. Use the template below to create your profile
5. Submit a pull request

## Profile Template

Create a new file in the `_people/` directory with the following format (or copy `_TEMPLATE.md` as a starting point):

```markdown
---
layout: page
title: Your Full Name
name: Your Full Name
position: Your Current Position (e.g., PhD Candidate, Postdoctoral Researcher)
institution: Your Institution
field: Your Field of Study
email: your.email@example.com
website: https://yourwebsite.com (optional)
twitter: yourtwitterhandle (optional, without @)
linkedin: https://linkedin.com/in/yourprofile (optional)
github: yourgithubusername (optional)
orcid: 0000-0000-0000-0000 (optional)
researchgate: https://researchgate.net/profile/yourprofile (optional)
image: /assets/images/people/your_filename.jpg (optional)
---

<div class="profile-header">
  {% if page.image %}
  <img src="{{ page.image | relative_url }}" alt="{{ page.name }}" class="profile-image">
  {% endif %}
  <div class="profile-header-text">
    <h1>{{ page.name }}</h1>
    <p class="profile-position">{{ page.position }}</p>
    <p class="profile-institution">{{ page.institution }}</p>
  </div>
</div>

# Your Full Name

## Bio

Write a brief bio about yourself (2-4 paragraphs). Include:
- Your current position and research focus
- Your academic background
- Any relevant professional experience
- Your interests and goals

## Research Interests

List your main research interests:
- Interest 1
- Interest 2
- Interest 3

## Current Projects

Describe your current research projects or activities.

## Publications (optional)

List your key publications if you'd like to share them.

## Contact

Include your contact information and social media links here.

<div class="contact-info">
  <a href="mailto:your.email@example.com"><i class="fas fa-envelope"></i> your.email@example.com</a>
  <a href="https://yourwebsite.com" target="_blank" rel="noopener noreferrer"><i class="fas fa-globe"></i> yourwebsite.com</a>
  <a href="https://twitter.com/yourhandle" target="_blank" rel="noopener noreferrer"><i class="fab fa-twitter"></i> @yourhandle</a>
  <a href="https://linkedin.com/in/yourprofile" target="_blank" rel="noopener noreferrer"><i class="fab fa-linkedin"></i> linkedin.com/in/yourprofile</a>
  <a href="https://github.com/yourusername" target="_blank" rel="noopener noreferrer"><i class="fab fa-github"></i> github.com/yourusername</a>
  <a href="https://orcid.org/0000-0000-0000-0000" target="_blank" rel="noopener noreferrer"><i class="fab fa-orcid"></i> ORCID: 0000-0000-0000-0000</a>
</div>
```

## Required Fields

The following fields in the YAML front matter (between the `---` lines) are required:
- `name`: Your full name
- `position`: Your current position
- `institution`: Your affiliated institution
- `field`: Your field of study

## Optional Fields

You can include any of the following social media and contact fields:
- `email`
- `website`
- `twitter`
- `linkedin`
- `github`
- `orcid`
- `researchgate`
- `googlescholar`
- `image`: Path to your profile image (see Profile Images section below)

## Profile Images

To add a profile image:

1. **Prepare your image**:
   - Format: JPG or PNG
   - Dimensions: 400x400 pixels minimum (square aspect ratio)
   - Size: Keep under 500KB
   - Professional headshot with clean background

2. **Add the image file**:
   - Place your image in `/assets/images/people/`
   - Name it to match your profile file (e.g., `firstname_lastname.jpg`)

3. **Update your profile**:
   - Add `image: /assets/images/people/your_filename.jpg` to your front matter

Your image will automatically display:
- As a circular avatar in the people directory listing
- As a profile picture on your individual profile page

See `/assets/images/people/README.md` for detailed image guidelines.

## Guidelines

- Keep your bio professional and concise
- Include accurate and up-to-date information
- Make sure all links work correctly
- Use proper markdown formatting
- Be respectful and inclusive in your language

## Questions?

If you have questions about adding your profile, please open an issue on GitHub.
