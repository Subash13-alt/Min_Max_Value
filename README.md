# 📊 Min-Max Finder using Divide and Conquer

This project is an interactive **Streamlit** web application that demonstrates the **Divide and Conquer** technique for finding the minimum and maximum values in an array. Users can either generate a random array or enter their own array, and the application computes the minimum and maximum values while tracking the number of comparisons made. It also compares the performance of the Divide and Conquer approach with the traditional Naive method.

The application provides a simple and user-friendly interface, making it an excellent learning tool for understanding **Divide and Conquer algorithms**, recursion, and algorithm analysis. It includes a performance comparison table for different input sizes, allowing users to observe how the Divide and Conquer approach reduces the number of comparisons compared to the Naive algorithm.

Built using **Python**, **Streamlit**, and the **random** module, this project is lightweight, interactive, and easy to deploy on **Streamlit Community Cloud**. It is suitable for students, educators, and developers who want to explore algorithm optimization, recursion, and time complexity through a practical implementation.

---

## 🚀 Features

- Generate a random array or enter a custom array
- Find the minimum and maximum values using Divide and Conquer
- Compare results with the Naive approach
- Display the number of comparisons performed by each algorithm
- Performance analysis for different array sizes
- Interactive and beginner-friendly web interface

---

## 🛠️ Technologies Used

- Python 3
- Streamlit
- Random Module

---

## 📂 Project Structure

```
Min-Max-Divide-Conquer/
│── app.py
│── requirements.txt
│── README.md
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/min-max-divide-conquer.git
```

Navigate to the project folder:

```bash
cd min-max-divide-conquer
```

Install the required package:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
streamlit run app.py
```

---

## ⏱️ Time Complexity

- **Divide & Conquer:** O(n)
- **Naive Method:** O(n)

Although both algorithms have linear time complexity, the Divide and Conquer approach requires fewer comparisons (approximately **3n/2 − 2**) than the Naive method (**2n − 2**), making it more efficient.

---

## 📄 License

This project is licensed under the MIT License.
