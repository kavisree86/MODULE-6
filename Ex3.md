# Ex.No:3
# Ex.Name :Write a CPP Program to REMOVE a Node from the Doubly Linked List Using STL and Display the same.
## Date:
## Aim:
To write a CPP Program to INSERT 5 data's into Doubly Linked List Using STL and Display the same

## Algorithm:

Start
Create a doubly linked list using list
Read 5 data elements from user
Insert each element using push_back()
Traverse the list using a for-each loop
Display all elements
Stop



## Program:
```
#include <iostream>
#include <list>

using namespace std;

int main() 
{
    list<int> gqlist1;
    int input;

    
    for (int i = 0; i < 5; ++i) 
    {
        cin >> input;
        gqlist1.push_back(input);
    }

    cout << "List 1 (gqlist1) is :  ";
    
    for (int value : gqlist1) 
    {
        cout << value << " ";
    }
    cout << endl;

    return 0;
}
```


## Output:
<img width="1176" height="332" alt="image" src="https://github.com/user-attachments/assets/43036aed-4172-4aab-bf38-776edd933544" />



## Result:

The Program Executed Successfully to INSERT 5 data's into Doubly Linked List Using STL and Display the same.
