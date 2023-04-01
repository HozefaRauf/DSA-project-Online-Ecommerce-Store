
# Online Ecommerce Store





## Introduction
The main idea of this project is to order product from the information provided. This project will focus on the development of a system for an online store that specializes in selling cameras. The system will be designed to streamline the process of managing inventory, processing orders, and handling customer information.

The project will utilize data structures and algorithms to efficiently manage the store's inventory and process orders. The system will also include features of a user-friendly interface for customers.

In addition to the features mentioned previously, this project will also incorporate the use of various data structures to enhance the efficiency and performance of the system.

Overall, this project will demonstrate the practical application of various data structures and algorithms in the design and development of an online shopping store management system that sells cameras, by providing efficient and optimized solutions for data storage, retrieval and pathfinding

## Implemented Data Structures
•	Linked List:

Linked lists are a data structure that allows for efficient insertion and deletion of elements.

Reason

The program uses linked lists to manage customer information and orders. The data of user (Delivery, Take Away) is saved in the linked List. We used Linked List instead of array because of dynamic size.

•	AVL (Adelson-Velsky and Landis) tree:

The AVL tree is a self-balancing binary search tree that is well-suited for storing large amounts of data and allows for fast insertion, deletion, and searching operations.

Reason

The AVL, for example, will be used to efficiently manage and maintain the store's inventory. All the operations of take away user is handled using AVL tree.  The operations like searching, deletion, insertion is done in a better way. The insertion and deletion is done by order ID that is given by the user.

•	Graphs:

Graphs has been used in the project to show the areas where the parcel can be delivered. Graphs are represented through adjacency matrix.





![](/images/11.png)


•	Graphs:

Graphs has been used in the project to show the areas where the parcel can be delivered. Graphs are represented through adjacency matrix.




•	Dijkstra’s algorithm:

Dijkstra's algorithm is used to implement efficient searching and navigation within the system. Dijkstra's algorithm is a shortest path algorithm that can be used to find the shortest path between two nodes in a graph. The nodes are represented as cities and this algorithm helps to provide the distance between cities.

Reason

This algorithm is often used in routing and as a subroutine in other graph algorithms. The nodes are represented as cities and this algorithm helps to provide the distance between cities.


![](/images/33.png)

•	Prim’s algorithm:

Prim's algorithm can be used to find the minimum spanning tree of a graph. So, it provides the distances between areas in a city.

Reason

Prims is used between areas in a city. The reason for using this is that we wanted to give discount to user  and previous distance is not used. The key idea behind Prim's algorithm is that at each step, we are adding a vertex to the tree that is connected to the tree by the minimum-weight edge. This ensures that the tree will have the minimum total weight of any spanning tree that can be formed from the graph.


![](/images/22.png)

## Product menu:
![](/images/44.png)

## Maps

1.Country

![](/images/55.png)

2.Islamabad

![](/images/66.png)

3.Abbotabad

![](/images/99.png)

4.Lahore

![](/images/77.png)

5.Karachi

![](/images/88.png)
