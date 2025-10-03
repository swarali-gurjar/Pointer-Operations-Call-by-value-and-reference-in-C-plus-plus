# Pointer-Operations-Call-by-value-and-reference-in-C-plus-plus

## Aim :

To study and implemet Pointer Operations (Call by value and Call by reference).

## Theory:

In C++, pointers are variables that store the memory address of another variable. They are powerful tools that allow direct access and manipulation of memory locations. With pointers, we can perform operations like accessing data, dynamic memory allocation, and efficient parameter passing to functions.

When passing arguments to functions, C++ provides different mechanisms:

**Call by Value**:

- In this method, a copy of the actual value is passed to the function.

- Changes made inside the function do not affect the original variable.

- It is safe but less efficient for large data since copying takes extra memory.

**Call by Reference**:

- Instead of passing a copy, the reference (or memory address) of the variable is passed.

- Any changes made inside the function directly affect the original variable.

- This method is more efficient and widely used when modifications are required.

## Algorithm: Salary Increment

**Step 1**: Start

**Step 2**: Input employee details: curr_sal (Current Salary) yr (Years worked) profit (Profit earned during working period) curr_proj (Research project status: Yes/No) tot_proj (Total projects completed)

**Step 3**: Initialize eligible = false.

**Step 4**: Check eligibility conditions: 

- If yr >= 1 OR If profit >= 100000 OR If curr_proj == "Yes"

-   If tot_proj >= 2 → Set eligible = true.

**Step 5**: If eligible == true: 

- Call function salary(&curr_sal) which increases curr_sal by 20%.

-   Store the returned value in new_sal.

- Display "You are eligible for a salary increment" and the new_sal.

**Step 6**: Else:

- Display *"You are not eligible for a salary increment at this time."

**Step 7**: End

## Conclusion

In this experiment, we understood how pointers work in C++ and how they can be used to access and manipulate memory directly.
We also learned the difference between call by value and call by reference. In call by value, only a copy of the variable is passed, so changes do not affect the original data. 
In call by reference (or using pointers), the actual variable is passed, so modifications inside the function reflect in the original value. This experiment showed how references and pointers make programs more efficient and flexible.

