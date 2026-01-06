CSC 466 Lab 7: Page Rank


Author: Matteo Shafer


# PageRank Algorithm

This Python program computes PageRank, a link analysis algorithm used by Google Search to rank web pages. It reads data from CSV files representing various networks and computes the PageRank scores for the nodes within those networks.


# Running the Program
1. Open a terminal or command prompt.
2. Navigate to the directory containing the Python script.
3. Run the program using the following command:	python pagerank.py [file_name.csv] [iterations]

# User Options
- `file_name.csv`: Replace file_name with the name of the CSV file with on of these files: 'NCAA_football.csv', 'dolphins.csv', 'lesmis.csv'.
- `iterations`: (Optional) Number of iterations for the PageRank algorithm. If not provided, the algorithm runs until convergence.

# Output
- The program generates a file with the PageRank scores named `[file_name]_pagerank_final.csv`.
- Statistics about the execution time and iterations are saved in a file named `[file_name]_statistics.txt`.



