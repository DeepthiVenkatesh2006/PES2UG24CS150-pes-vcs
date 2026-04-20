# PES-VCS Mini Project

## 👤 Student Details

* Name: Deepthi V
* SRN: PES2UG24CS150

---

## 📌 Project Description

This project implements a simplified version control system similar to Git.
It includes object storage, tree structure, indexing, and commit functionality.

---

## ⚙️ Features Implemented

### Phase 1: Object Storage

* Blob storage using SHA-256 hashing
* Deduplication of objects
* Integrity verification

### Phase 2: Tree Structure

* Directory snapshot representation
* Deterministic serialization

### Phase 3: Indexing

* File staging using index
* Index load and save operations

### Phase 4: Commit System

* Commit creation
* Reference update (`refs/heads/main`)
* Integration with object storage

---

## 🧪 How to Run

```bash
make
./test_objects
./test_tree
./test_sequence.sh
```

---

## 📸 Screenshots

Screenshots of outputs and results are included in the `screenshots/` folder.

---

## 🧠 Concepts Used

* File handling in C
* Hashing (SHA-256)
* Data structures (tree representation)
* Version control concepts

---

## ✅ Conclusion

Successfully implemented a basic version control system with core functionalities similar to Git.
