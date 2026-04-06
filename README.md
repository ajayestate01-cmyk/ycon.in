Ycon Infra - Transforming Spaces
A modern, high-performance landing page for Ycon Infra, a leading real estate developer. This project features a clean, architectural aesthetic focusing on luxury, sustainability, and innovation.

🚀 Features
Modern UI/UX: Built with a "Montserrat" and "Open Sans" typography pairing for a professional corporate look.

Fully Responsive: Leverages Tailwind CSS for a seamless experience across mobile, tablet, and desktop.

React Integration: Uses a component-based architecture for manageable sections like Stats and Navigation.

Floating WhatsApp Integration: A persistent, branded contact button to drive user engagement.

Visual-Heavy Design: High-quality image placeholders and architectural banners to showcase property standards.

🛠️ Tech Stack
HTML5 & CSS3: Semantic structure and custom branding styles.

Tailwind CSS: For rapid, utility-first styling.

React.js (v18): Handled via CDN for modularity without a heavy build step.

Babel: Used to compile JSX in the browser (Development mode).

FontAwesome: For high-quality iconography.

📂 File Structure
Plaintext
ycon-infra/
├── index.html    # Main HTML structure and React application logic
└── style.css     # External stylesheet for custom branding and animations
⚙️ Installation & Usage
Since this project uses CDN links for all dependencies, no installation (like npm install) is required.

Clone the repository:

Bash
git clone https://github.com/your-username/ycon-infra.git
Open the project:
Simply double-click index.html or use a "Live Server" extension in VS Code to view the site.

🎨 Customization
Changing the Branding
To update the primary brand color, modify the CSS variable in style.css:

CSS
:root {
    --ycon-green: #YOUR_HEX_CODE;
}
Updating Contact Info
To change the WhatsApp number or default message, edit the constants in the App component within index.html:

JavaScript
const whatsappNumber = "7568005371";
const whatsappMessage = encodeURIComponent("Your custom message here");
📝 License
This project is open-source and available under the MIT License.
