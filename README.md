# HI gen AI Course Flyer - Multiple Versions

This repository contains multiple responsive versions of the HI gen AI course flyer, each tailored for different target audiences while maintaining consistent design and functionality.

## 📁 File Structure

```
HI-gen-AI/
├── index.html              # General version (original)
├── index-academic.html     # Academic-focused version
├── index-industry.html     # Industry-focused version
├── versions.html           # Navigation hub for all versions
├── README.md              # This documentation
└── .git/                  # Git version control
```

## 🎯 Available Versions

### 1. **General Version** (`index.html`)
- **Target Audience:** Broad audience including academics, industry professionals, engineers, and teachers
- **Use Case:** General marketing, open enrollment, mixed audiences
- **Key Features:** Balanced content for multiple professional backgrounds

### 2. **Academic Version** (`index-academic.html`)
- **Target Audience:** University staff, researchers, faculty, PhD students, administrative staff
- **Use Case:** Academic institutions, research organizations, educational marketing
- **Key Features:** 
  - Research-focused messaging
  - Academic integrity emphasis
  - Teaching and administrative applications

### 3. **Industry Version** (`index-industry.html`)
- **Target Audience:** Business leaders, marketing professionals, operations managers, product teams
- **Use Case:** Corporate training, business development, industry partnerships
- **Key Features:**
  - Business-focused messaging
  - Competitive advantage emphasis
  - Corporate applications

## 🚀 Quick Start

1. **View All Versions:** Open `versions.html` in your browser for a navigation hub
2. **Direct Access:** Open any specific version file directly
3. **Customization:** Modify content in any version while maintaining the responsive design

## 📱 Responsive Design Features

All versions include:
- **Mobile-first design** with Tailwind CSS
- **Responsive typography** using `clamp()` functions
- **Breakpoint system:** `sm:`, `md:`, `lg:` for different screen sizes
- **Print-friendly styles** for professional printing
- **Accessibility features** with proper semantic HTML

## 🔧 Version Management

### Git Branching Strategy
```bash
# Current branch: version-academic
git branch                    # List all branches
git checkout main            # Switch to main branch
git checkout version-academic # Switch to academic version
git checkout -b new-version  # Create new version branch
```

### Making Changes
1. **Create a new branch** for major changes
2. **Edit the specific version** you want to modify
3. **Test responsiveness** on different devices
4. **Commit changes** with descriptive messages
5. **Push to GitHub** to save all versions

### Adding New Versions
1. Copy an existing version file
2. Rename it (e.g., `index-engineering.html`)
3. Modify content for the new target audience
4. Add a version badge in the header
5. Update `versions.html` navigation
6. Commit and push changes

## 🎨 Customization Guide

### Content Customization
- **Header:** Modify title, subtitle, and version badge
- **Target Audience:** Update "Who Should Attend?" section
- **Learning Outcomes:** Adjust based on audience needs
- **Footer:** Customize call-to-action messaging

### Design Customization
- **Colors:** Modify CSS variables in the `<style>` section
- **Typography:** Adjust responsive font sizes
- **Layout:** Modify grid systems and spacing
- **Images:** Replace or update illustrations

## 📊 Version Comparison

| Feature | General | Academic | Industry |
|---------|---------|----------|----------|
| Target Audience | Mixed | University Staff | Business Professionals |
| Key Focus | Broad AI skills | Research & Teaching | Business Applications |
| Professional Cards | 4 mixed roles | 4 academic roles | 4 business roles |
| Learning Outcomes | General AI usage | Academic integrity | Business efficiency |
| Footer CTA | "Transform Your Work" | "Transform Academic Work" | "Transform Your Business" |

## 🔄 Maintenance

### Regular Updates
- **Content:** Update course dates, prerequisites, contact information
- **Design:** Ensure responsive design works on new devices
- **Links:** Verify all external links are working
- **Images:** Check that all images load correctly

### Version Control Best Practices
- **Commit frequently** with clear messages
- **Use descriptive branch names** (e.g., `version-engineering`)
- **Test all versions** before pushing to main
- **Keep versions synchronized** for common updates

## 📞 Support

For questions about the flyer versions or customization:
- **Email:** genai-courses@chalmers.se
- **Course Website:** www.chalmers.se/genai-hands-on

## 📄 License

© Chalmers University of Technology

---

**Last Updated:** December 2024  
**Version:** 1.0  
**Responsive Design:** Yes  
**Print-Friendly:** Yes
