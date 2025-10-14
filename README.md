```python
Lists to store your books
Library = []
Wishlist = []

Add a book you already own
Book = input("Enter the name of a book you own:\n")
if Book:
    print("Good!")
    Library.append(Book)
else:
    print("OK.")

Add a book you wish to have
Wish = input("Enter the name of a book you wish to have:\n")
if Wish:
    print("Nice!")
    Wishlist.append(Wish)

Show your current lists
print("Your library:", Library)
print("Your wishlist:", Wishlist)

Combine all books into one library
Current_library = []
Current_library.extend(Library)
Current_library.extend(Wishlist)
print("All books in your collection:", Current_library)

Donate a book
Book_to_donate = input("Enter the name of a book from your library you wish to donate:\n")
if Book_to_donate in Current_library:
    Current_library.remove(Book_to_donate)
    print(f"{Book_to_donate} has been donated.")
else:
    print("Sorry, that book is not in your library.")

Final view of your library
print("Final library after donation:", Current_library)
---

📚 Book Collection Manager

This is a simple Python project designed to help manage a personal library and wishlist of books.  
It was built as part of my Python learning journey (up to unit 4).

💡 Project Features

- Add books to your *library* (books you already own).
- Add books to your *wishlist* (books you want to have).
- View your current *library and wishlist*.
- Merge both lists into one *complete collection*.
- *Donate* a book from your collection.
- View the *updated collection* after donation.

🧠 What I Learned

Through this project, I practiced:

- List operations: `append()`, `extend()`, `remove()`.
- Conditional statements: `if`, `else`.
- User input handling: `input()`.
- Basic error checking.
- Printing and organizing outputs.

🛠️ Technologies

- Python 3

📝 How It Works

1. The user is asked to enter the name of a book they already own.
2. Then, they enter a book they wish to have.
3. The program displays both lists.
4. It combines them into a complete collection.
5. The user is asked if they want to donate a book.
6. If the book exists, it's removed from the collection.
7. The final updated library is shown.

📌 NoteThis project was written without using a computer — only using a phone and a lot of motivation. It's a small but meaningful step in my journey to becoming a *Cybersecurity Expert*.

---
