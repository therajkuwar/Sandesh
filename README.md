# Sandesh
DSA Miniproject

Our project, a basic email simulator developed in C++, boasts a range of key features and employs various data structures for efficient user account management and message handling.

Key Features:

  1) User Account Management: Users can create, log in, change passwords, and delete their accounts.
  2) Messaging: Logged-in users can send messages to other existing users.
  3) Message Management: Users can view their received, sent, deleted, and starred messages.
  4) Search Functionality: Users can search for messages sent to or received from a specific user.
  5) Message Actions: Users can read, delete, and mark messages as important (star) or unstar them.
  6) Trash: Deleted messages are stored in a trash folder, and users can either permanently delete or view them.

Data Structures Used:

  1) Doubly Linked List: Used to store user accounts. It allows for efficient user management operations.
  2) Singly Linked Lists (Per User): Two singly linked lists per user to store sent and received messages. This structure organizes messages for each user.
  3) Vector: Utilized for storing references to messages that match search criteria and deleted messages. This simplifies message management and retrieval operations.
Overall, this project demonstrates how various data structures and algorithms can be applied to create a basic email system with user account management and message handling capabilities in C++.
