<img width="1299" alt="image" src="https://github.com/user-attachments/assets/0f4a083b-1869-4984-9c60-ae59a1c39e6c" />

## 📖 Project Overview

This project analyzes the influence and interactions of characters across a book series using graph theory. We leverage **NetworkX**, a powerful Python library for network analysis, to compute character relevance and visualize their influence dynamics over multiple books.

The analysis focuses on centrality metrics to evaluate the importance of selected characters within the network of interactions.

## 🎯 Objectives

- Import and clean book network data
- Build graph networks using NetworkX
- Calculate degree centrality scores for selected characters
- Visualize the evolution of character influence across the book series

## 🛠 Technologies Used

- Python 3.x
- NetworkX
- Pandas
- Matplotlib

## 📂 Project Structure

books/  
NetworkX_Character_Influence_Book_Series.ipynb  
README.md  
requirements.txt (optional)

## 🚀 How to Use

### 1️⃣ Clone the Repository

<!-- You would normally run this in bash -->
<!-- git clone https://github.com/your-username/networkx-character-influence-book-series.git -->

### 2️⃣ Prepare the Dataset

Place the CSV files for each book inside the `books` folder. Each CSV should contain at least the following columns:

- `Source`: character name
- `Target`: character name
- `weight`: number of interactions between characters

### 3️⃣ Open the Notebook

Open `NetworkX_Character_Influence_Book_Series.ipynb` in Jupyter Notebook or Jupyter Lab.

### 4️⃣ Run the Analysis

The notebook will:

- Load and merge data
- Create graph networks per book
- Compute degree centrality for specified characters
- Plot the evolution of relevance scores across books

## 📝 Example Output

The notebook generates a line plot showing how the influence of key characters changes across the books, providing clear insights into character development and importance.

## ⚠ Notes

- The metric used is degree centrality. Other metrics like betweenness or closeness centrality can be explored for richer insights.
- The `duration` edge attribute (if present) is ignored; only `weight` is considered.

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
