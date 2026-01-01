# Contact-Book-Application
**BSBA 23 Project – 23F-4046, 5012, 5013**

A complete Python-based Contact Book system that validates input, encrypts sensitive data, stores contacts efficiently, saves them to a file, and provides a console-based menu. Includes sample data for quick startup and a main menu for smooth program management.

## Features
- **Validation:** Names, phone numbers, emails, and addresses are validated; duplicates prevented.
- **Encryption:** Email and address use a simple Caesar Cipher (+3/-3) for privacy.
- **Contact Class:** Handles creation, updating, and string representation of contacts.
- **Storage Class:** Maintains contacts in a list and dictionary for fast search, update, and deletion.
- **File Handling:** Loads and saves contacts from `contacts.txt`; handles broken lines gracefully.
- **Contact Manager:** Add, view, search, update, delete, and sort contacts.
- **Menu System:** Console menu for easy navigation.
- **Sample Data Loader:** Loads sample contacts if no file is found.
- **Data Source Choice:** User can load from file or sample data at startup.

## Data Structures
- **List:** Stores contacts in insertion order; supports looping and sorting.
- **Dictionary:** Maps phone numbers to contacts for O(1) lookups and duplicate prevention.
- **File Storage:** Line-by-line storage in `contacts.txt`; rewrites file on updates.
- **Encryption:** Modified Caesar Cipher for emails and addresses; simple but not highly secure.

## Main Flow
1. Choose data source (file or sample data).  
2. Load contacts into Storage.  
3. Start Menu loop for user interactions.  
4. Perform operations via Contact Manager.  
5. Save data automatically on exit.

## Notes
- Designed for small datasets; ideal for learning and basic usage.  
- Validation and encryption enhance usability and privacy.  
- Combines list and dictionary for balance between simplicity and performance.
