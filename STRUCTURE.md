# Proposed Organisational Structure

This document outlines a suggested organisational structure for the GCSE Python Code repository. The structure is designed to help teachers and students easily find and contribute code examples relevant to the AQA and OCR exam boards.

## Directory Structure

```
gcse/
├── README.md                    # Main repository readme
├── STRUCTURE.md                 # This document
├── CONTRIBUTING.md              # Guidelines for contributions
│
├── aqa/                         # AQA exam board specific examples
│   ├── README.md
│   ├── fundamentals/            # Programming fundamentals
│   │   ├── variables.py
│   │   ├── data_types.py
│   │   ├── operators.py
│   │   └── input_output.py
│   ├── control-flow/            # Selection and iteration
│   │   ├── if_statements.py
│   │   ├── while_loops.py
│   │   └── for_loops.py
│   ├── data-structures/         # Arrays, lists, dictionaries
│   │   ├── lists.py
│   │   ├── strings.py
│   │   └── 2d_arrays.py
│   ├── subroutines/             # Functions and procedures
│   │   ├── functions.py
│   │   ├── parameters.py
│   │   └── return_values.py
│   ├── file-handling/           # File operations
│   │   ├── reading_files.py
│   │   ├── writing_files.py
│   │   └── csv_handling.py
│   ├── algorithms/              # Standard algorithms
│   │   ├── linear_search.py
│   │   ├── binary_search.py
│   │   ├── bubble_sort.py
│   │   └── merge_sort.py
│   └── sql/                     # SQL examples (embedded in Python)
│       └── sqlite_examples.py
│
├── ocr/                         # OCR exam board specific examples
│   ├── README.md
│   ├── fundamentals/            # Programming fundamentals
│   │   ├── variables.py
│   │   ├── data_types.py
│   │   ├── operators.py
│   │   └── input_output.py
│   ├── control-flow/            # Selection and iteration
│   │   ├── if_statements.py
│   │   ├── while_loops.py
│   │   └── for_loops.py
│   ├── data-structures/         # Arrays, lists, dictionaries
│   │   ├── lists.py
│   │   ├── strings.py
│   │   └── 2d_arrays.py
│   ├── subroutines/             # Functions and procedures
│   │   ├── functions.py
│   │   ├── parameters.py
│   │   └── return_values.py
│   ├── file-handling/           # File operations
│   │   ├── reading_files.py
│   │   ├── writing_files.py
│   │   └── csv_handling.py
│   ├── algorithms/              # Standard algorithms
│   │   ├── linear_search.py
│   │   ├── binary_search.py
│   │   ├── bubble_sort.py
│   │   └── merge_sort.py
│   └── robust-programs/         # Input validation and testing
│       ├── validation.py
│       └── error_handling.py
│
├── common/                      # Examples applicable to both exam boards
│   ├── README.md
│   ├── string-manipulation/     # String handling techniques
│   │   ├── string_methods.py
│   │   ├── slicing.py
│   │   └── formatting.py
│   ├── maths/                   # Mathematical operations
│   │   ├── random_numbers.py
│   │   ├── rounding.py
│   │   └── modulus.py
│   └── real-world-examples/     # Practical programming scenarios
│       ├── calculator.py
│       ├── quiz_game.py
│       └── password_checker.py
│
└── past-papers/                 # Solutions to past paper questions
    ├── README.md
    ├── aqa/
    │   ├── 2023/
    │   ├── 2022/
    │   └── 2021/
    └── ocr/
        ├── 2023/
        ├── 2022/
        └── 2021/
```

## Topic Categories

### 1. Programming Fundamentals
- Variables and constants
- Data types (integers, floats, strings, booleans)
- Operators (arithmetic, comparison, logical)
- Input and output

### 2. Control Flow
- Selection (if, elif, else)
- Iteration (for loops, while loops)
- Nested structures

### 3. Data Structures
- Lists/Arrays (1D and 2D)
- Strings and string manipulation
- Dictionaries (OCR focus)
- Records/Tuples

### 4. Subroutines
- Defining and calling functions
- Parameters and arguments
- Return values
- Local and global variables

### 5. File Handling
- Reading from text files
- Writing to text files
- Working with CSV files

### 6. Algorithms
- Linear search
- Binary search
- Bubble sort
- Merge sort (higher tier)

### 7. Robust Programs
- Input validation
- Error handling (try/except)
- Authentication routines

## Naming Conventions

- Use lowercase with underscores for file names: `bubble_sort.py`
- Use descriptive names that indicate the topic
- Include difficulty level in filename if appropriate: `arrays_advanced.py`

## Code Standards

Each Python file should include:
1. A docstring explaining what the code demonstrates
2. Clear comments explaining key concepts
3. Example usage or test cases where appropriate
4. GCSE-appropriate coding style (simple and readable)

## Example File Template

```python
"""
Topic: [Topic Name]
Exam Board: AQA/OCR/Both
Specification Reference: [e.g., AQA 3.2.1]
Difficulty: Foundation/Higher/Both

Description:
Brief explanation of what this code demonstrates.
"""

# Example code here
def example_function():
    """Example function demonstrating the concept."""
    pass

# Test/demonstration
if __name__ == "__main__":
    # Example usage
    example_function()
```

## Contributing

When adding new code examples:
1. Place files in the appropriate exam board folder
2. Use the correct topic subfolder
3. Follow the naming conventions above
4. Include the standard file template with docstrings
5. Ensure code is tested and runs correctly

## Benefits of This Structure

1. **Easy Navigation**: Teachers and students can quickly find relevant examples
2. **Exam Board Specific**: Clear separation between AQA and OCR requirements
3. **Topic-Based Organisation**: Logical grouping by curriculum topic
4. **Past Paper Solutions**: Dedicated area for exam practice solutions
5. **Scalable**: Easy to add new topics or exam years as needed
