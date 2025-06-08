# linked-list-stack-queue-cpp
Implementasi struktur data Stack &amp; Queue menggunakan Single Linked List dalam bahasa C++

# 📚 Stack & Queue menggunakan Single Linked List (C++)

Project ini adalah implementasi struktur data **Stack** dan **Queue** menggunakan **Single Linked List** dalam bahasa C++. Program ini dibuat sebagai latihan konsep dasar struktur data, serta bisa digunakan untuk memahami bagaimana cara kerja operasi-operasi seperti push, pop, enqueue, dan dequeue secara manual.

---

## 🚀 Fitur

🔹 Stack:
- Push (menambahkan data ke akhir list)
- Pop (menghapus data dari akhir list)
- Cetak isi Stack
- Clear (menghapus seluruh data)

🔹 Queue:
- Enqueue (menambahkan data ke akhir list)
- Dequeue (menghapus data dari awal list)
- Cetak isi Queue
- Clear (menghapus seluruh data)

🔹 Gabungan Stack & Queue:
- Push (enqueue)
- Pop
- Dequeue
- Cetak data
- Clear

---

## 🧠 Struktur Data

Semua operasi menggunakan **Single Linked List**, dengan `struct node` sebagai elemen dasar:

cpp
struct node {
    int data;
    node *next;
};


💻 Cara Menjalankan Program
Untuk menjalankan program C++ ini di komputer kamu, ikuti langkah-langkah berikut:

🔧 1. Siapkan Compiler C++
Pastikan kamu sudah menginstal compiler seperti:
Windows: MinGW
Linux/Mac: Biasanya sudah ada g++, atau bisa install via terminal:
  sudo apt install g++

📁 2. Simpan File
Simpan file program kamu dengan ekstensi .cpp, misalnya:
stack.cpp
queue.cpp
stack_queue.cpp

🧪 3. Compile Program
Buka terminal atau command prompt, lalu pindah ke direktori tempat file kamu berada.

Contoh compile (gunakan g++):
  g++ stack.cpp -o stack
  g++ queue.cpp -o queue
  g++ stack_queue.cpp -o stack_queue
  
Penjelasan:
g++ = compiler C++
-o = output file (hasil compile)

▶️ 4. Jalankan Program
Setelah berhasil di-compile, kamu bisa menjalankan programnya:

🪟 Di Windows (Command Prompt):
  stack.exe
  queue.exe
  stack_queue.exe
🐧 Di Linux/Mac:
  ./stack
  ./queue
  ./stack_queue

📝 Contoh Output Terminal:
  ------Operasi Stack------
  [1] PUSH
  [2] POP
  [3] CETAK
  [4] CLEAR
  [5] KELUAR
  Pilih Menu :

👤 Author
Nama: Muhammad Hasrul Waliyudin
Kampus: UNP Kediri
Instagram: @mhasrulw
GitHub: Hasrull14

  
🏷️ Tags : 
 •C++ • Data Structure • Linked List • Stack • Queue • CLI • DSA
