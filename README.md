# half-subtractor
Here’s a neat **GitHub-friendly description** you can use for your **Half Subtractor** project 👇

---

### 🔹 Half Subtractor

The **Half Subtractor** is a combinational circuit used for performing the subtraction of two binary bits. It has:

* **Inputs:** `A` (minuend) and `B` (subtrahend)
* **Outputs:**

  * **Difference (D):** Represents `A ⊕ B`
  * **Borrow (B\_out):** Represents `A' · B`

#### ⚡ Truth Table

| A | B | Difference (D) | Borrow (B\_out) |
| - | - | -------------- | --------------- |
| 0 | 0 | 0              | 0               |
| 0 | 1 | 1              | 1               |
| 1 | 0 | 1              | 0               |
| 1 | 1 | 0              | 0               |

#### 📝 Logic Expressions

* **Difference (D) = A ⊕ B**
* **Borrow (B\_out) = A' · B**

#### 📌 Applications

* Used in **ALUs** for binary subtraction.
* Forms the basic building block for **Full Subtractor
