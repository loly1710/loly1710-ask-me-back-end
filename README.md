# ASK ME
---
## Description

An open platform for everyone where users can post questions or problems they face and seek answers or solutions from others. Users can publish their inquiries by selecting the type of problem or question.


## User Stories
- **As a new user**, I want to sign up using my email and password, so that I can create an account to interact with the platform.
- **As a registered user**, I want to sign in using my email and password, so that I can access my account.
- **As a logged-in user**, I want to:
  - Post a question with a title, description, and tags.
  - Edit my posted question to correct errors or add more information.
  - Delete my question if necessary.
  - Add an answer to a question.
  - Edit my answer to fix errors or provide better explanations.
  - Delete my answer if it’s no longer relevant or appropriate.
  - Add a comment to a question or answer.
  - Edit my comment to fix mistakes or clarify my input.
  - Delete my comment to remove unwanted content.
  - View questions categorised by tags to easily find topics of interest.

---

## Data Models
![ERD](assests/ERD.PNG)

---

## Wireframes
### 1. Home Page
![Home Page Wireframe](![image_720](https://github.com/user-attachments/assets/20bd2e74-e4ab-406a-822d-f6c8d3eac5d8)
)

### 2. Questions Page
![Sign-Up Page Wireframe](![image_720](https://github.com/user-attachments/assets/a890860e-8286-4a2c-a2f7-eb5ee5092f1c)
)

### 3. Question Details Page
![Question Details Wireframe](![image_720](https://github.com/user-attachments/assets/d91602ad-6502-4f6e-8119-3acfc79e3b42)
)

### 4. Post New Question
![User Dashboard Wireframe](![image_720](https://github.com/user-attachments/assets/e5c48fed-0ed0-461c-9541-d665c47b13a8)
)

---
## Technologys
1. React
2. jsx
3. Css
4. javaScript

---
## Pseudocode

### Signing Up
1. User provides email and password.
2. Validate email format and password strength.
3. Create a new user account in the database.
4. Confirm the account creation.

### Signing In
1. User provides email and password.
2. Check credentials against the database.
3. Create a session for the user.
4. Confirm login success.

### Posting a Question
1. Check if the user is logged in.
2. Accept title, description, and tags.
3. Save the question to the database, linked to the user ID.
4. Confirm successful posting.

### Editing a Question
1. Verify user ownership of the question.
2. Accept updated details.
3. Update the question in the database.
4. Confirm successful update or return an error if unauthorized.

### Deleting a Question
1. Verify user ownership of the question.
2. Remove the question from the database.
3. Confirm deletion or return an error if unauthorized.

### Adding an Answer
1. Check if the user is logged in.
2. Accept the answer content.
3. Save the answer to the database, linked to the question and user IDs.
4. Confirm successful addition.

### Editing an Answer
1. Verify user ownership of the answer.
2. Accept updated content.
3. Update the answer in the database.
4. Confirm successful update or return an error if unauthorized.

### Deleting an Answer
1. Verify user ownership of the answer.
2. Remove the answer from the database.
3. Confirm deletion or return an error if unauthorized.

### Adding a Comment
1. Check if the user is logged in.
2. Accept the comment content.
3. Save the comment to the database, linked to the relevant question/answer and user IDs.
4. Confirm successful addition.

### Editing a Comment
1. Verify user ownership of the comment.
2. Accept updated content.
3. Update the comment in the database.
4. Confirm successful update or return an error if unauthorized.

### Deleting a Comment
1. Verify user ownership of the comment.
2. Remove the comment from the database.
3. Confirm deletion or return an error if unauthorized.



### futur work 
1. Like button for post, comment and replay.
2. close the post so no more replays.
