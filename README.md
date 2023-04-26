# Binary-Search  

Binary Search is defined as a searching algorithm used in a sorted array by repeatedly dividing the search interval in half.  
The idea of binary search is to use the information that the array is sorted and reduce the time complexity.

**Binary search can be implemented only on a sorted list of items. If the elements are not sorted already, we need to sort them first.**  

![Binary-Search-GeeksforGeeks](https://user-images.githubusercontent.com/91966613/234466509-2d3ac2a5-473f-4f2a-8326-19123b8f55ea.gif)


1. The array in which searching is to be performed is:  
![image](https://user-images.githubusercontent.com/91966613/234463742-54dd5273-7cf1-49ed-af15-fc48a7332006.png)  
Let x = 4 be the element to be searched.

2. Set two pointers low and high at the lowest and the highest positions respectively.  
![image](https://user-images.githubusercontent.com/91966613/234463882-8a071cb1-ecaa-441d-9094-cc4d7505b3e6.png)

3. Find the middle element mid of the array ie. arr[(low + high)/2] = 6.  
![image](https://user-images.githubusercontent.com/91966613/234463961-45bba711-57d2-4c9e-9da8-d4037ccca6d1.png)  

4. If x == mid, then return mid.Else, compare the element to be searched with m.  
5. If x > mid, compare x with the middle element of the elements on the right side of mid. This is done by setting low to low = mid + 1.
6. Else, compare x with the middle element of the elements on the left side of mid. This is done by setting high to high = mid - 1.  
![image](https://user-images.githubusercontent.com/91966613/234464185-42401a39-0383-4b94-a88e-3af135b1b68b.png)
7. Repeat steps 3 to 6 until low meets high.  
![image](https://user-images.githubusercontent.com/91966613/234464277-6675a7e9-7374-4ad3-bdf4-b5a037fbcd77.png)
8. x = 4 is found.  
![image](https://user-images.githubusercontent.com/91966613/234464380-580a0aac-bfc1-4bf3-8df3-8992f64d197a.png)

### OUTPUT SCREENSHOTS
![image](https://user-images.githubusercontent.com/91966613/234464662-dcce5107-e303-40fa-a459-2a439eb236bd.png)  
![image](https://user-images.githubusercontent.com/91966613/234464739-30aea32f-dc66-4266-b5f7-ae4a15f4fcbd.png)  







