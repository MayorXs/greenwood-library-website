# greenwood-library-website
A collaborative web project by Morgan and Jamie as part of the 'My Darey.io Git Adventure

### 🎯 Objective
Set up the GitHub repository and initialize the base project structure using Visual Studio Code (VS Code) to simulate a collaborative Git workflow for the "My Darey.io Git Adventure" capstone project.

---

### 🧱 Repository Setup

1. **Created a new GitHub repository**
   - **Name:** `greenwood-library-website`
   - **Description:** Collaborative project by Morgan and Jamie simulating real-world Git practices for the Darey.io capstone assignment.
   - Initialized with a `README.md` file.


##  Creating Base HTML Files on the Main Branch

### 🎯 Objective
Simulate the initial version of the Greenwood Library Website by creating placeholder HTML files and committing them directly to the `main` branch using Visual Studio Code.

---

### 🔨 Steps Performed

1. **Created the following HTML files in VS Code**:

   - `home.html`
   - `about_us.html`
   - `events.html`
   - `contact_us.html`

2. **Added Sample Content to Each File**:

```html
<!-- home.html -->
<h1>Welcome to the Greenwood Community Library</h1>
<p>This is the homepage of your favorite local library.</p>

<!-- about_us.html -->
<h2>About Us</h2>
<p>We are a community-driven library serving Greenwood and its surroundings.</p>

<!-- events.html -->
<h2>Upcoming Events</h2>
<p>Stay tuned for exciting book readings, workshops, and storytime sessions.</p>

<!-- contact_us.html -->
<h2>Contact Us</h2>
<p>Email: info@greenwoodlibrary.org | Phone: 123-456-7890</p>


---

### 👤 Morgan's Contribution: Add Book Reviews Section

#### 🛠️ Branch: `add-book-reviews`

Morgan created a new feature branch to add a Book Reviews section to the community library website.

1. Created and switched to a new branch:
   
   git checkout -b add-book-reviews


---

### 👤 Morgan's Contribution – Book Reviews Section

#### 🛠 Branch: `add-book-reviews`

Morgan worked on creating a new page for Book Reviews as part of the collaborative Git workflow simulation.

**Steps Completed:**


1. Created a feature branch named `add-book-reviews`.
2. Added a new file `book_reviews.html` with placeholder content.
3. Staged, committed with message: `"Add book reviews section"`.
4. Pushed the branch to GitHub.
5. Opened a Pull Request titled: `"Add book reviews section"`.
6. Successfully merged the PR into the `main` branch.

### 👤 Jamie's Contribution: Update Events Page

#### 🛠️ Branch: `update-events`

Jamie updated the Events page with new community events following the same Git workflow as Morgan.

**Steps Completed:**

1. Created and switched to feature branch:
   
   git checkout -b update-events

<h2>June 2023 Community Events</h2>
<ul>
  <li>Summer Reading Kickoff - June 5</li>
  <li>Author Talk: Jane Doe - June 15</li>
</ul>


### 👤 Jamie's Workflow: Syncing Before PR

#### 🔄 Pulling Latest Changes Before PR Creation

After completing updates to `events.html` but before raising the Pull Request:

1. **Staged and committed local changes**:
   ```bash
   git add events.html
   git commit -m "Updated events page with community events"
   git pull origin main

### 🔄 Jamie's Pre-PR Synchronization

**Before raising the PR**, Jamie ensured the `update-events` branch was synced with latest `main`:

1. **From the update-events branch**:
   ```bash
   git checkout update-events
