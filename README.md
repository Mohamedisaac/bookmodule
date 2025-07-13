# Book Module
Drupal like module template web app

This Canvas provides a responsive website template designed to organize content in a hierarchical, book-like structure.

Here's a description of its key features and purpose:

* **Purpose:** The template is ideal for creating online guides, manuals, documentation, FAQs, or any content that benefits from a structured, chapter-based organization. It aims to replicate the intuitive navigation of a physical book in a web format.

* **Structure and Navigation:**
    * **Hierarchical Sidebar:** A dynamic sidebar on the left displays the table of contents, allowing users to easily browse through main chapters, sections, and sub-sections.
    * **Content Display Area:** The main area on the right is where the content of the selected page is displayed.
    * **Sequential Navigation:** "Previous" and "Next" buttons (visible on all screen sizes in the current version) at the bottom of the content area enable users to move through the pages sequentially.
    * **Back to Home:** A "Back to Home" button in the header allows users to return to a central homepage (which can list multiple guides).

* **Responsiveness:** The layout is fully responsive, adapting seamlessly to different screen sizes (desktops, tablets, and mobile phones). The sidebar collapses into a hamburger menu on smaller screens, and an overlay helps manage the sidebar's visibility.

* **Technology Stack:** It's built using:
    * **HTML:** For the basic structure of the web pages.
    * **Tailwind CSS:** A utility-first CSS framework for rapid and consistent styling, ensuring a clean and modern look.
    * **Vanilla JavaScript:** For all interactive elements, dynamic content loading, and navigation logic, without relying on external JavaScript libraries or frameworks (beyond Tailwind's own JS for some components if used).

* **Content Management (Data-driven):** The content for the guide is managed directly within a JavaScript array (`bookData`). This makes it easy to add, remove, or modify pages and their hierarchy by simply updating this data structure, without needing to alter the HTML markup for each page.

* **User Experience:** The template prioritizes a clean, intuitive user experience, making it easy for readers to find and consume information within structured documents.
