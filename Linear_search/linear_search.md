# Problem no:1
## problem name: linear search algorithm

## Algorithm 
1. Start a loop from the first index
2. Compare it with the target value
3. if value is equal to the target value then break the loop
4. Value not equal to the target then move on to the next index


## Code Snippet
```cpp
array  = [1,2,3,4,5,6]
target = 4
found =false;

    for(int i=0;i<size;i++){
        if(array[i]==target){
            cout<<"Found the target at index "<<i<<endl;
            found = true;
            break;
        }
    }

    if(!found)cout<<-1;
```
a full code is given in the  file where you can input an array and a target value . If target is present it will let you know by giving the index of the target else it will return -1;

### [Code link](linear_search.cpp)

## input
```cpp
array =[1,2,3,4,5,6]
target = 4
```
## output 
```cpp
found the target
```