## Assignment

### Brief

Write your answers for each question:

Imagine you are hired by a startup company for a school to implement their IT infrastructure as their IT consultant. n your own words (300 words or less), describe how could implementing Scrum help their IT team improve their productivity.

```
Your answer here
Scrum helps the team deliver high-quality and high-value work faster, adapt to changes efficiently which ensures infrastructure (e.g., cloud servers, student portals) evolves with real-time feedback and maintains transparency. 

Faster Delivery – Scrum breaks work into short Sprints (2-4 weeks), enabling the team to deliver functional IT solutions (e.g., LMS setups, network configurations) incrementally and focusing on clear, short-term goals. This helps avoid the chaos of juggling multiple tasks at once and ensures steady progress 

Flexibility - Scrum ensures quick wins and adaptability to changing school needs. For a startup, where priorities can shift rapidly, Scrum allows the team to pivot easily without derailing long-term goals.

Clear Priorities – The Product Owner (e.g., school admin) defines priorities in the Backlog, ensuring the team focuses on high-impact tasks (e.g., cybersecurity first, then Wi-Fi optimization).

Daily Accountability – Daily Stand-ups (15-minute meetings) keep the team aligned, surface blockers (e.g., delayed hardware shipments), and promote quick problem-solving. By involving stakeholders regularly, Scrum ensures that the IT solutions being developed stay relevant to the school’s evolving needs—whether it's setting up networks, managing devices, or rolling out educational platforms. The team quickly identifies roadblocks and adjusts priorities in real time. This open communication fosters accountability and keeps everyone aligned

Continuous Improvement – After each Sprint, the Retrospective lets the team refine processes (e.g., automate user onboarding) to eliminate inefficiencies.
It allows the team to reflect on what worked, what didn’t, and how to get better next time.

Transparent Collaboration – Scrum’s Kanban-style boards (To Do/Doing/Done) provide visibility, reducing miscommunication between IT, teachers, and management.
```

Question 2:
Write ten (10) user stories for a book-borrowing website for a library. Write it in the format: `As a ____, I want to ____, so that _____`.

```
As a student, I want to search for books by title, author, or genre, so that I can quickly find what I need.

As a library member, I want to reserve a book online, so that I can pick it up later when it's available.

As a librarian, I want to manage book inventory (add/remove/edit books), so that the catalog stays up to date.

As a user, I want to see my borrowing history, so that I can track past reads and due dates.

As a borrower, I want to renew a book online, so that I can extend my loan period if needed.

As a guest, I want to create an account, so that I can borrow books and access member features.

As a librarian, I want to receive overdue book alerts, so that I can follow up with borrowers.

As a member, I want to receive email notifications for due dates, so that I avoid late fees.

As a user, I want to leave ratings/reviews for books, so that others can see recommendations.

As an admin, I want to generate reports on popular books and borrowing trends, so that I can optimize the library’s collection
```

Question 3: 
Define [Acceptance Criteria](https://resources.scrumalliance.org/Article/need-know-acceptance-criteria) for 3 to 5 user stories out of the 10 user stories you have defined.

```
1. User Story: Search for Books
As a student, I want to search for books by title, author, or genre, so that I can quickly find what I need.

Acceptance Criteria:
Search Functionality: User can enter keywords in a search bar. Results display books matching title, author, or genre.

Filters: User can refine results by availability (checked-in/out), format (e-book/print), or publication year.

Empty State: If no matches, display: “No results found. Try a different search.”

2. User Story: Reserve a Book
As a library member, I want to reserve a book online, so that I can pick it up later when it's available.

Acceptance Criteria:
Reservation Flow: User clicks "Reserve" on an unavailable book.

System confirms reservation and adds user to a waitlist.

Notifications: User receives an email/SMS when the book is ready for pickup.

Time Limit: Reservation is held for 3 days before auto-canceling.

3. User Story: View Borrowing History
As a user, I want to see my borrowing history, so that I can track past reads and due dates.

Acceptance Criteria:
History Display: Lists all borrowed books with title, borrow date, and return date.

Sorting: User can sort by most recent, overdue, or alphabetical order.

Privacy: History is only visible to the logged-in user (not admins/librarians).

4. User Story: Renew a Book
As a borrower, I want to renew a book online, so that I can extend my loan period if needed.

Acceptance Criteria:
Renewal Conditions: Book can be renewed only if: No other user has reserved it. User has not exceeded max renewals (e.g., 2 renewals per book).

Confirmation: System shows new due date after renewal.

Overdue Block: User cannot renew if the book is already overdue.

5. User Story: Overdue Alerts for Librarian
As a librarian, I want to receive overdue book alerts, so that I can follow up with borrowers.

Acceptance Criteria:
Alert Triggers: Email/SMS sent to librarian 1 day after due date and weekly thereafter.

Alert Content: Includes borrower name, book title, and days overdue.

Manual Override: Librarian can mark alerts as "resolved" (e.g., if book is returned offline)
```


### Submission 

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL. 


### References

_Example of Referencing Classmate_

Referenced the code block below from Terence.
```js
    function printMe(){
        console.log("I am a reference example");
    }
```

_Example of Referencing Online Resources_

- https://developer.mozilla.org/en-US/
- https://www.w3schools.com/html/
- https://stackoverflow.com/questions/14494747/how-to-add-images-to-readme-md-on-github
