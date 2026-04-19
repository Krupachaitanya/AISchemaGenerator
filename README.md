# AI Schema Generator - Landing Page

A premium, highly responsive modern landing page for the **AI Schema Generator** VS Code Extension. This webpage serves as the front-facing demonstration and documentation portal for the extension, explaining its features, workflow, and technical architecture.

<img width="1859" height="1061" alt="image" src="https://github.com/user-attachments/assets/6094839c-281b-488a-acd5-415f9376aa15" />
<img width="1856" height="1059" alt="image" src="https://github.com/user-attachments/assets/1086caad-89cd-46ed-a874-734d7041c07f" />
<img width="1847" height="1079" alt="image" src="https://github.com/user-attachments/assets/e5c51c14-92f7-4c90-ae97-b80c40f693e1" />


## 🌟 Showcase Features

- **Dark Mode Glassmorphism**: Utilizes high-end web design principles including frosted glass UI components and deep glowing ambient backgrounds.
- **Fully Responsive Layout**: Scales seamlessly down to smartphones and up to ultra-wide desktop displays using Flexbox and CSS Grid.
- **Dynamic Scroll Animations**: Contents fluidly fade and slide into view natively as the user scrolls.
- **Video Demonstration Block**: Features a dedicated HTML5 `<video>` container ready to play actual usage instructions or CLI setups.

## 🚀 Build Tech

Built purposefully using vanilla web technologies to ensure extremely lightweight, lightning-fast loads without dependencies:
- **HTML5**: Semantic and accessible document structure.
- **CSS3**: Custom variables, micro-animations, mobile fluid media queries, and aesthetic gradients styling.
- **Vanilla JavaScript**: DOM targeting, advanced `IntersectionObserver` scroll animations, and page reload handling.
- **Lucide Icons**: Crisp, vector SVGs for UI components.

## 📂 Architecture Structure

```text
📁 AI-Schema-Landing-Page/
├── 📄 index.html    # Main HTML layout, structure, and text content
├── 📄 styles.css    # Premium design variables, glassmorphic styles, and responsive @media queries
├── 📄 script.js     # Intersection observer handling animations and smooth anchor scroll behaviors
└── 📄 README.md     # Project documentation
```

## 🛠️ How to View Locally

Because this project uses vanilla HTML, CSS, and JS, there is absolutely zero backend setup or complex Node processes required! You can launch the site instantly:

1. Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/Krupachaitanya/AISchemaGenerator.git
   ```
2. Navigate into the folder:
   ```bash
   cd AISchemaGenerator
   ```
3. Simply double click on the `index.html` file to open it in any web browser (Chrome, Edge, Firefox). 
*(Optionally, you can use a VS Code Extension like "Live Server" for live-reloading if you wish to edit code)*

## 🎬 How to Add Your Own Custom Demo Video

To replace the dummy sample placeholder movie with your actual VS Code extension workflow screen-recording:
1. Export and copy your real `.mp4` video inside this project's top-level directory.
2. Open `index.html` in your editor.
3. Scroll down to the `<!-- Video Demo Section -->` (approximately around Line 125).
4. Replace the `src` link attribute with your own video file's name:

   ```html
   <!-- Replace this: -->
   <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4">
   
   <!-- With this: -->
   <source src="my_extension_demo.mp4" type="video/mp4">
   ```
5. Save the file and refresh your browser!

---
*© 2026 Keshavsoft. All rights reserved.*
