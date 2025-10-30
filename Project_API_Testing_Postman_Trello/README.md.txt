# Trello API Testing Project  
*Author: Bohdan Mamlai*  
*Date: [YYYY-MM-DD]*  

---

## Project Overview  
This project demonstrates API testing of the :contentReference[oaicite:0]{index=0} using :contentReference[oaicite:1]{index=1}. It contains eight tasks that cover the full CRUD lifecycle for boards, lists, and cards — from creation, updating, deletion, to retrieval.  
The goal was to show proficiency in functional and negative API testing, use of environment variables, and clear documentation of test cases and results.

---

## Tools & Technologies  
- Postman (for API requests and automated verification scripts)  
- Trello REST API  
- Excel / Google Sheets (for task tracking and documentation)  
- JavaScript (Postman test scripts)  
- Environment variables for dynamic request chaining  

---

## Task Breakdown  
The tasks covered are:  
1. **Create Board** — Create a new board for further testing.  
2. **Create Left List** — Add a list at the top position of the board (`pos=top`).  
3. **Create Right List** — Add a list at the bottom position of the board (`pos=bottom`).  
4. **Create Card in Left List** — Add a card into the left list created previously.  
5. **Create Card in Right List** — Add a card into the right list created previously.  
6. **Delete Card** — Remove one of the cards created in previous tasks to validate deletion logic.  
7. **Get Cards on Board** — Retrieve all current cards on the board to verify state and structure.  
8. **Update Board** — Update the board’s name and description to validate update functionality.

---

## Documentation Link  
You can view the detailed task sheet here: [Spreadsheet Link](https://docs.google.com/spreadsheets/d/1JVbtwgEbOfWf5fYm5wFAYW1juBa3h03Z8zoFpfRxs00/edit?usp=sharing)

---

## How to Run the Tests  
1. Import the Postman collection (`Trello_QA.postman_collection.json`).  
2. Set up the environment (`Trello QA`) with variables:  
   - `apiKey` — your Trello API key  
   - `apiToken` — your Trello API token  
3. Run the tasks in sequence:  
   - Create Board → Create Left List → Create Right List → Create Left Card → Create Right Card → Delete Card → Get Cards on Board → Update Board  
4. For each request the tests automatically validate status codes, response times, and field types.  
5. Review results and screenshot evidence stored in the `/screenshots` folder.

---

## Results & Findings  
All tasks executed successfully with expected behavior.  
Key outcomes:  
- Created board and lists, added cards, deleted a card, and updated board details.  
- Environment variables were chained across tasks for dynamic execution.  
- Response times were within acceptable limits (< 1000ms) and field types matched documentation.  
- Deleted card verification confirmed resource removal via 404 responses.

---

## Next Steps  
- Add negative test scenarios (invalid token, missing parameters, invalid IDs) to increase coverage.  
- Expand tests to include bulk card operations or membership/label functionality.  
- Consider adding a CI integration to run the Postman collection automatically.
