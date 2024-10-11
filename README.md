# ContactManager14

ContactManager14 is a simple command-line application written in Java that allows users to manage their contacts. The application supports adding, displaying, and deleting contacts, with an additional feature of encrypting and decrypting the contact data using AES encryption.

## Features

- **Add Contact**: Add a contact with a name and phone number. The contact is encrypted before being saved.
- **Display Contacts**: Display all the saved contacts by decrypting the contact information.
- **Delete Contact**: (To be implemented) Remove a contact from the list after decrypting the stored data.
- **Encryption**: All contact information is stored in an encrypted format using AES encryption for enhanced security.

## Technologies Used

- **Java**: Core programming language.
- **Java Cryptography Extension (JCE)**: Used for AES encryption and decryption of contact data.
- **Serialization**: Used for storing and retrieving contact objects from a file.

## Prerequisites

Before running the ContactManager14 application, make sure you have the following:

- **Java Development Kit (JDK)** version 8 or later installed.
- A terminal or command-line interface (CLI) for running the program.

## How to Run

### 1. Clone the repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/Kabilash01/ContactManager.git
cd ContactManager
