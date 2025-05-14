# Django Blog Application

A complete blog platform with post creation, comments, and user authentication built with Django.

## Features

- **Blog Posts**
  - Create, edit, and delete posts
  - Draft system with publish functionality
  - Rich text editing capabilities
- **Comments System**
  - Comment approval workflow
  - Threaded comments
- **User Authentication**
  - Login-protected actions
  - Author-specific permissions
- **Views**
  - Class-based views for CRUD operations
  - Draft list view
  - About page

## Models

### Post
- Author (ForeignKey to User)
- Title (CharField)
- Text (TextField)
- Creation/Publish dates
- Approval methods

### Comment
- Related Post (ForeignKey)
- Author (CharField)
- Text (TextField)
- Approval status
- Creation date

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Ekaterina-hub140/blog_project.git
   cd blog_project
