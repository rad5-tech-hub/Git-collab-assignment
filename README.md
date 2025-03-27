# Git Collaboration Assignment Instructions

## **Objective**

In this assignment, you will collaborate using Git and GitHub to create and style a webpage using **HTML and CSS**. You will work as a team to practice version control, branching, merging, and resolving conflicts.

---

## **Instructions**

### **1. Fork & Clone the Repository**

1.  **Fork the repository** on GitHub to your own account.
2.  **Clone the repository** to your local machine using the following command in your terminal:
    ```sh
    git clone <your-forked-repo-url>
    ```
3.  **Navigate into the project folder** using the `cd` command:
    ```sh
    cd <repository-name>
    ```

### **2. Setting Up Your Branch**

1.  **Create a new branch** for your assigned task. Use a descriptive name that includes your name:
    ```sh
    git checkout -b feature-yourname
    ```
2.  **Work on your assigned task** within this branch. This could involve:
    * Modifying the `index.html` file to add structured content.
    * Modifying the `style.css` file to apply styles.
    * Making design updates.

### **3. Editing the Files**

* **`index.html`:** Add well-structured content using appropriate HTML tags (headings, paragraphs, lists, links, images, etc.). Ensure your HTML is semantic and accessible.
* **`style.css`:** Apply styles to the HTML elements using CSS. Focus on colors, fonts, layout, and responsiveness to create a visually appealing and functional webpage.
* **Code Quality:** Ensure your HTML and CSS code is clean, well-formatted, and includes comments to explain your changes and the purpose of different sections.

### **4. Committing and Pushing Changes**

1.  **Add your changes** to the staging area:
    ```sh
    git add .
    ```
2.  **Commit your changes** with a clear and meaningful message that describes what you have done:
    ```sh
    git commit -m "Added navbar styling"
    ```
3.  **Push your branch** to your forked repository on GitHub:
    ```sh
    git push origin feature-yourname
    ```

### **5. Creating a Pull Request**

1.  **Go to GitHub** and navigate to your forked repository.
2.  **Click the "Compare & pull request" button** that should appear, prompting you to request a merge into the `main` (or `master`) branch of the original repository.
3.  **Add a detailed description** of the changes you have made in your pull request. Explain the purpose of your branch and the specific updates you implemented.
4.  **Submit the pull request.** Your team members can then review your changes and discuss potential merges.