### Test Case 1: Card Sort Functionality

**Preconditions:**

* User is on a Trello board page
* At least one list exists on the board

**Steps:**

1. Click **“Add a card”** under any list.
2. Add a card with a single-letter title.
3. Repeat step 2 three more times using different letters.
4. Click the **List actions (three dots …)** at the top right of the list.
5. Click **“Sort…”** or **“Sort by…”** from the menu options.
6. Select **“Card name (alphabetically)”**.

**Expected Result:**

* The cards in the list are reordered alphabetically from top to bottom.

### Test Case 2: Auto-Sort by Due Date

**Preconditions:**

* User is on a Trello board page
* At least one list exists on the board
* The list contains at least three cards with different due dates

**Steps:**

1. Click the **List actions (three dots …)** at the top right of the list.
2. Click **“Sort by…”** from the menu options.
3. Select **“Due date”** from the available sorting criteria.
4. Observe the order of cards in the list.

**Expected Result:**

* The list is automatically sorted in ascending order by due date, with the earliest due date appearing at the top.

### Test Case 3: Rename Card

**Preconditions:**

* User is on a Trello board page
* At least one list exists on the board
* At least one card with text exists in the list

**Steps:**

1. Hover over an existing card in the list.
2. Click the **edit (pencil)** icon that appears on the right side of the card.
3. Replace the existing card title text with a new name.
4. Click **“Save”** to confirm the change.

**Expected Result:**

* The card title is updated successfully and displays the new text on the board.
