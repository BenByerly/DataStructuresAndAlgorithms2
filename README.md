This C++ program manages and sorts a list of counties based on their populations using a doubly linked list and merge sort. The main() function reads data from a CSV file (counties_ten.csv) or (counties_list.csv) containing information about counties, including their index, name, state, and population. Each county is represented as a County object. These county objects are dynamically allocated and appended to a custom List class, which stores them in a doubly linked list.

The List class supports basic operations like appending a new element, printing the list, and performing a merge sort on the counties based on their population in descending order. The merge sort algorithm is implemented as a private method within the List class, splitting the list into smaller partitions, sorting them, and then merging them back together. Once sorted, the program prints out the list of counties along with their respective populations.

The County class encapsulates county attributes and provides comparison operators (< and >) to compare two counties based on their population, which is essential for the sorting algorithm. It also overloads the << operator to format the output when printing county information.

In summary, this program reads county data, stores it in a linked list, sorts it using merge sort based on population, and then prints the sorted list.
