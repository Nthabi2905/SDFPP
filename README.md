# 🌟 Nthabiseng Moloi — Responsive Resume Website

This is my fully responsive resume website built using **HTML** and **Tailwind CSS**.  
The goal of this project was to translate a Figma design into a pixel-perfect website while demonstrating layout skills, responsive development, and clean code structure.

The site includes my profile information, skills, proficiency bars, projects, education, experience, and clickable contact details.

---

## 🎯 Project Purpose

This project forms part of the CodeSpace Academy curriculum.  
The aim was to:

- Recreate a professional resume layout based on a design file.
- Build a fully responsive webpage (mobile → desktop).
- Use clean HTML structure and Tailwind CSS effectively.
- Implement best practices for layout, spacing, and component styling.
- Present the project in a recorded walkthrough.

---

## 🎥 Project Walkthrough Video

You can watch the full walkthrough here:  
[▶️ Click to view the video](https://drive.google.com/file/d/1cRoF2Beqf3lja3iqoDzITQMV3UxQSirw/view?usp=sharing)

---

## 🛠️ Technologies Used

- **HTML5**
- **Tailwind CSS**
- **CSS Flexbox & Grid**
- **Responsive Design (mobile-first)**
- **External Icon Libraries (Devicon, Icons8, Tailwind icon)**

---

## 📚 Sections Included

### 🔹 **1. Header / Introduction**

- Profile image + introduction text
- Matching height layout using grids
- Pixel-perfect styling from Figma

### 🔹 **2. Proficiency Section**

- Styled progress bars with percentage widths
- Two-column grid layout
- Custom spacing values from Figma

### 🔹 **3. Skills Tags**

- Flexible chips using Tailwind utilities
- Soft background colors
- Wraps neatly across screen sizes

### 🔹 **4. Projects Section**

- Four project cards
- Hover effects, shadows, transitions
- Responsive grid (1 → 2 → 4 columns)

### 🔹 **5. Education & Tools Section**

- Two-column layout on desktop, stacked on mobile
- Dynamic tool icons arranged in grid
- Categories: Languages, Design Tools, Developer Tools
- Icons sourced from external CDNs

### 🔹 **6. Experience Section**

- Styled experience cards
- “Most Recent” badge using absolute positioning
- Hover color transitions

### 🔹 **7. Footer With Clickable Links**

- Email (mailto)
- LinkedIn
- GitHub
- Mobile and desktop layout

---

## 🎨 Design Decisions

- Followed the Figma design exactly, including:
  - Padding and spacing
  - Custom border-radius values
  - Color variables
  - Typography scaling
- Used Tailwind arbitrary values (e.g. `rounded-[29.04px]`) for accuracy.
- Ensured sections line up cleanly with consistent spacing.

---

## 🔧 Icon Challenges & Solutions

I used icons from:

- **Devicon CDN**
- **Icons8**
- **Tailwind CSS official icon**
- **Flaticon**

Some icons came in different colors. I adjusted their appearance to match the Figma theme.

### ⚠️ Challenge:

Changing the color of external SVG icons to white on hover **did not work**, because the SVGs contain fixed fill colors.

### 🛠️ My Solution:

I discovered that external SVGs cannot be recolored unless:

- You download the SVG
- Replace the `fill` attributes with `currentColor`
- Then use Tailwind classes like `text-white`

This is something I will apply in future improvements.

---

## 📱 Responsiveness

The entire site is mobile-first and adjusts smoothly using:

- `grid-cols-1` → `xl:grid-cols-2` / `xl:grid-cols-4`
- `flex-wrap`
- Custom heights on desktop (`xl:h-[300px]`)
- Utility classes for text and spacing adjustments

I showcased this in my recorded presentation.

---

## 🎥 Presentation Video

My project walkthrough video (5–10 minutes) can be accessed here:

👉 **Google Drive Link:** _Add your link here_  
_(Make sure sharing is set to “Anyone with the link can view”)_

---

## 📂 File Structure

index.html
README.md
assets/
├── Project.jpg
├── heart.png

---

## 🧠 What I Learned

- How to read a Figma design and reproduce it accurately.
- Tailwind responsive utilities (`xl:` prefixes).
- Grid and Flexbox layout combinations.
- Managing spacing, alignment, and component grouping.
- How external SVG icons behave with color changes.
- Creating hover effects and transitions.
- Organising HTML in a clean, readable structure.

---

## 🚀 Future Improvements

- Replace external SVGs with custom editable ones.
- Add scroll animations or fade-in transitions.
- Deploy to GitHub Pages or Netlify.
- Convert the project into a React-based component structure.

---

## 📝 Submission Checklist

✔ Uploaded project to GitHub  
✔ Included README with video link  
✔ Shared presentation via Google Drive  
✔ Followed naming conventions  
✔ Submitted GitHub link to the LMS

---

## 💛 Acknowledgements

Thank you to CodeSpace Academy for the guidance, design resources, and support throughout the project.

---
