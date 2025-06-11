# COMP 271 Week 02 Reflection

## Comparison with Leo's Solutions

### Week 00 Assignment (Array Operations)
- **What I got right**:
  - Correctly identified the smallest element in the array
  - Understood the need to create a new array when removing elements
  - Implemented proper array copying logic

- **Close but not quite**:
  - My initial solution used a single loop with conditionals instead of two separate loops
  - Variable naming wasn't as clear as in Leo's solution (e.g., `smallest_index` vs my less descriptive names)

- **Missed the mark**:
  - Didn't include as thorough comments explaining the array copying logic
  - Missed some edge cases in initial testing (empty array scenario)

- **Lessons learned**:
  - Breaking operations into clear, separate steps (like using two distinct loops) improves readability
  - More descriptive variable names make code self-documenting
  - Need to consider all edge cases from the beginning

### Week 01 Assignment (Handling Empty Arrays)
- **What I got right**:
  - Recognized the need to handle empty arrays
  - Implemented null return for empty array case

- **Close but not quite**:
  - My solution was more verbose than Leo's compact version
  - Used more complex conditional logic than necessary

- **Missed the mark**:
  - Didn't consider using the ternary operator for concise null checking
  - Initial version didn't properly box the primitive return value

- **Lessons learned**:
  - Simpler solutions are often better (like using ternary operator)
  - Need to be more familiar with autoboxing in Java
  - Should look for opportunities to reuse existing methods (like getSmallest3 calling getSmallest)

## Code Quality Evaluation

### Comments
- My initial comments were less detailed than Leo's solutions
- Need to better explain the "why" behind code decisions, not just the "what"
- Learned the value of clear comments explaining loop boundaries and array operations

### Testing
- Initially didn't test edge cases thoroughly enough
- Learned to test with:
  - Empty arrays
  - Arrays with duplicate minimum values
  - Arrays of different sizes
- Now understand the importance of systematic testing

## Improvement Plan

### Challenges Faced
1. Initially underestimated the importance of comments
2. Tended to write more complex solutions than necessary
3. Didn't always consider all edge cases upfront

### Improvement Steps
1. **Before coding**:
   - Write pseudocode with clear comments
   - Identify all edge cases to test
   - Look for opportunities to reuse existing methods

2. **During coding**:
   - Use more descriptive variable names
   - Break operations into clear, separate steps
   - Look for simplest possible solution

3. **After coding**:
   - Review against provided solutions
   - Add additional test cases
   - Refactor for clarity

### Measurement
- Compare future assignments against model solutions
- Track reduction in bugs found during testing
- Monitor improvement in code review feedback