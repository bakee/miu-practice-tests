## Question 5

Write a function to return an array containing all elements common to two
given arrays containing distinct positive integers. You should not use any inbuilt
methods. You are allowed to use any number of arrays.

The signature of the function is:
```java
int[] f(int[] first, int[] second)
```

Examples:

| if the input parameters are    | return                                                       |
|--------------------------------|--------------------------------------------------------------|
| {1,8,3,2},{4,2,6,1}            | {1,2}                                                        |
| {1,8,3,2,6},{2,6,1}            | {2,6,1}                                                      |
| {1,3,7,9},{7,1,9,3}            | {1,3,7,9}                                                    |
| {1,2}, {3,4}                   | {}                                                           |
| {}, {1,2,3}                    | {}                                                           |
| {1,2}, {}                      | {}                                                           |
| {1,2}, null                    | null                                                         |
| null, {}                       | null                                                         |
| null, null                     | null                                                         |