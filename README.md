# Quiz2

# List Processing Program

## Description

This Java program processes two predefined lists (`list1` and `list2`) to generate a third list (`list3`) by mapping indices from `list1` to values in `list2`. The program demonstrates basic list operations and index mapping in Java.

## Program Structure

### Package
- `oop.q2` - The package containing the main program

### Classes
- `Main` - The main class containing the program logic

### Key Components
1. **Predefined Lists**:
   - `list1`: A list of integers serving as indices (4, 0, 2, 3, 1, 6, 5, 7, 8, 9, 10, 11, 12)
   - `list2`: A list of strings ("AA", "BB", "CC", ..., "QQ")

2. **Processing Method**:
   - `processLists()`: Generates `list3` by mapping each element from `list1` to the corresponding index in `list2`

3. **Output**:
   - Prints `list3` with each element's index and value

## How It Works

1. **Initialization**:
   - `list1` is initialized with 13 integer values representing indices
   - `list2` is initialized with 18 string values

2. **Processing**:
   - For each integer in `list1`:
     - Retrieves the corresponding string from `list2` at that index
     - Adds the string to `list3`
     - Handles potential index out of bounds scenarios

3. **Output**:
   - Prints `list3` in the format:
     ```
     0: EE
     1: AA
     2: CC
     ...
     ```

## Example Output
