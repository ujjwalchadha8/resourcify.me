# Understanding the concept of ArrayList :

> Authors : Divyansh Pratap Singh ([twitter](https://twitter.com/))

# Array List vs Array :

| Array List | Array |
| :--- | ---: |
|they have variable size| they have fixed size|
|they have non-continous memory allocation | they have continous memory allocation |
|they can store only objects | they can store primitive data-types ex. int , float |

# Implementing ArrayList

        '''
        import java.util.ArrayList;
        public class arrayy_list{
            public static void main(String[]args){

                ArrayList<Integer> list = new ArrayList<Integer>();

            }
        }
        '''
> Similarly for declaring String
'''
ArrayList<String> name = new  ArrayList<String>();

'''

# Adding element  in ArrayList

> we use add function to add an element in ArrayList
'''
ArrayList<Integer> list = new ArrayList<Integer>();

list.add(3);

'''
> Adding elements 3,2,5,0 --> below is the complete code for adding element
'''
import java.util.ArrayList;
        public class arrayy_list{
            public static void main(String[]args){

                ArrayList<Integer> list = new ArrayList<Integer>();

                list.add(3);
                list.add(2);
                list.add(5);
                list.add(0);
            }
        }
'''

# Accessing elements of ArrayList :

> to access element in ArrayList we  use get function . Inside get function we  pass the index position of the element .


'''
list.get(0);

'''
> Gives us : 3

# Adding element in middle of ArrayList : 

 > add  function adds an element at the end of the ArrayList ; to add element at any position in ArrayList we use add function and pass 2 parameters ;

'''
list.add(<indexposition><element>);

list.add(0,9);
'''
> Result : [9,3,2,5,0]

# Changing element in ArrayList :

> to change a value in ArrayList we  use set function . The function takes  2 parameters ;  1st is the index position of the element you want to change and the 2nd parameter is the new element.

'''
list.set(0,8);
'''
> Result : [8,3,2,5,0]

# removing an element from ArrayList :

> to remove a element from ArrayList we use remove function and pass the element index position as the  parameter.

'''
list.remove(0);
'''
> Result : [3,2,5,0]

# printing complete ArrayList

'''
System.out.println(<ArrayList name >);
System.out.println(list);

'''
> Result : [3,2,5,0]
