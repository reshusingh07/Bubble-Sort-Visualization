# Sorting Algorithm Visualization : Quick Sort
  An algorithm like Quicksort algorithm is hard to understand theoretically. We can understand easily by visualizing such kind of algorithms. In this article, a program that visualizes the

## Quicksort Algorithm

has been implemented.The Graphical User Interface(GUI) is implemented in python using

[pygame](https://www.geeksforgeeks.org/introduction-to-pygame/)


library.

 ## Approach:

An array of random values is generated and are drawn as lines(bars) in the window.

Since the algorithm performs the operation very fast, pygame.time.delay() has been used to slow down the process.

Assign specific keys for each operation (start sorting, reset bars).

The actions are performed using ‘pygame.event.get()’ method, which stores all the events which user performs.

Different colors are used to indicate types of bar.

Green – Unsorted bar

Blue – Pivot bar

Orange – Sorted bar


## Example:
 ### Input:
 Press “Enter” key to Perform Visualization.Press “r” key to generate new array.
 
### Output:Initial:
 ![intial_quick_sort](https://github.com/user-attachments/assets/f3692418-d322-45a9-9b7a-2d346bd1f413)

 ### Sorting:
 ![sorting_quick_sort](https://github.com/user-attachments/assets/34c2856c-f622-4ce9-80bd-cc1eef445e71)

### Final:
![final_quick_sort](https://github.com/user-attachments/assets/9a6e8103-adef-4dae-a944-9af5321acea3)
