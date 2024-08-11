# reachinbox-frontend-dev-assignment
Deployed Link :

https://reachinbox-seven.vercel.app/
## Overview

ReachInbox is a revolutionary AI-driven platform transforming cold outreach. It's an all-in-one solution for businesses to effortlessly find, enrich, and engage high-intent leads using multi-channel outreach across Twitter, LinkedIn, email, and phone. ReachInbox acts as your AI-powered growth team, continuously generating top-tier leads and enhancing large-scale cold email marketing campaigns.

## Project Details

This project, named "One Box", is a Next.js application that shows emails and helps users reply to them. It includes features such as user authentication, email fetching, reply functionality, keyboard shortcuts, a custom text editor, and both light and dark modes.

## Features

1. **User Authentication**: Implemented login page using the provided design.
2. **Email Viewing**: Fetch and display emails in the OneBox screen after login.
3. **API Integration**:
   - GET /onebox/list
   - GET /onebox/:thread_id
   - DELETE /onebox/:thread_id
4. **Keyboard Shortcuts**:
   - "D" to delete an email
   - "R" to open the reply box
5. **Custom Text Editor**: Added custom buttons like "SAVE" and "Variables" in the text editor.
6. **Reply Functionality**: Implemented sending replies using the API.
   - POST /reply/:thread_id
     ```json
     {
       "from": "email",
       "to": "email",
       "subject": "",
       "body": ""
     }
     ```
7. **Light and Dark Mode**: Supports both themes.

## ScreenShot :
* Login Page :
  
![reachinbox-login](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/0cf863cc-38b8-4b4c-9dc6-f73770eb285b)

* Home Page :
  
![reachinbox-homePage](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/796ed6a2-7516-46f3-bcf0-107dc7a4bfca)

* Email List Page :
  
![reachinbox-emaillist](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/f078f8ec-3d16-4fdd-ba9b-3513d8d0e87d)

* Email Reply Page :
  
![reachinbox-rely](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/3fc3ebb4-37c3-42ae-8618-a4506926a989)

* Email Delete Page :
  
![reachinbox-delete](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/505f5fe4-6e90-491d-92c4-dd16c986f972)

* Light Mode Page :
  
![reachinbox-lightmode](https://github.com/GaneshGourav/reachinbox-frontend-assignment/assets/119353884/8ca2741a-3022-414d-99ff-3f4251f24e34)

## Setup

### Prerequisites

- Node.js
- npm (or yarn)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/abhijha910/reachinbox-frontend-assignment.git
   cd reachinbox-frontend-assignment
   ```

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

### Running the Project

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Usage

1. **Login**: Navigate to the login page and authenticate using your credentials.
2. **View Emails**: After logging in, you will be taken to the OneBox screen where you can view your emails.
3. **Keyboard Shortcuts**: Use "D" to delete an email and "R" to open the reply box.
4. **Reply to Emails**: Use the custom text editor to compose and send replies.
5. **Switch Theme**: Toggle between light and dark modes using the provided option in the UI.




It is showing empty data list for the mail list url:

![Alt text](public/blankData.png)
