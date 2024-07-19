# Submitter Journal System 

Welcome to the Submitter Journal System, a comprehensive solution for managing journal submissions, reviews, and publications. This system is designed to facilitate the interaction between authors, reviewers, and editors through an intuitive Graphical User Interface (GUI).

## Introduction

The Submitter Journal System is a robust platform designed to streamline the process of submitting, reviewing, and managing academic journal articles. This system provides distinct interfaces for public users, authors, reviewers, and editors, ensuring a smooth and efficient workflow for all participants involved in the journal publication process.

### Public Access Pages

- **Home Page (`home.php`)**: The home page provides a list of all available journals. Users can browse through the journals and click on a journal name to view more details about the volumes and articles associated with it.
- **Journal Details Page (`journal.php`)**: This page displays detailed information about a specific journal, including its publication frequency and a list of volumes. Users can click on a volume to view the articles published within it.
- **Volume Details Page (`volume.php`)**: On this page, users can see information about a specific volume and the articles it contains. The page also shows the reviewers assigned to each article if available. Clicking on an article title allows users to view the full content of the article.
- **Article View Page (`article.php`)**: This page displays the complete content of an article, including its title, abstract, authors, submission date, and the review result. Reviewer information is not displayed to the public for privacy reasons.

### Author Interface

- **Author Login Page (`author.php`)**: Authors can log in using their email address. This page grants them access to their submitted articles.
- **Author Home Page (`authorHome.php`)**: After logging in, authors can see a list of their submitted articles along with their statuses (Accepted, Rejected, Pending, or Revision). The page also displays the second submission deadline if the article is under revision.

### Reviewer Interface

- **Reviewer Login Page (`reviewer.php`)**: Reviewers log in using their email address. This login page provides access to articles assigned to them for review.
- **Reviewer Home Page (`reviewerHome.php`)**: Once logged in, reviewers can see a list of articles they need to review. This page simplifies the review process by organizing articles in a user-friendly manner.

### Editor Interface

- **Editor Panel - Journal Selection (`editor.php`)**: Editors start by selecting a journal to manage. This page lists all journals in the system.
- **Editor Panel - Volume Selection (`editor.php`)**: After selecting a journal, editors choose a specific volume to edit. The page displays volumes associated with the selected journal.
- **Editor Panel - Article and Reviewer Assignment (`editor.php`)**: This page allows editors to manage articles submitted to the selected volume. Editors can view assigned reviewers and assign new reviewers from a list of potential candidates.

## Graphical User Interface (GUI)

The GUI is designed to be user-friendly and intuitive, ensuring that users can easily navigate and perform their tasks. The interface simplifies the interaction with the journal submission system, making it efficient for authors, reviewers, and editors to manage their respective roles.

## Technologies Used

The Submitter Journal System  is built using a range of technologies to ensure a robust, secure, and efficient platform:

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript

- **Backend**:
  - PHP

- **Database**:
  - MySQL

- **Security**:
  - Password hashing
  - Session management

- **Additional Tools**:
  - Composer for dependency management

## Conclusion

The Submitter Journal System  provides a comprehensive solution for managing the submission, review, and publication processes of academic journals. By offering tailored interfaces for public users, authors, reviewers, and editors, the system ensures an efficient and streamlined workflow, enhancing the overall user experience and facilitating the management of journal articles.

