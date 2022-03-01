# Unit 1 - Unit Testing
## Pre-requirements
- [JUnit](https://junit.org/junit5/docs/current/user-guide/), [Mockito](https://site.mockito.org)
- All code must be in test package
- 100% Green test suite cases

## Tasks
1. Using next test class 
```java
public class NumbersTest {

    @Test
    public void shouldHave100Numbers() {
        // Definition
        List<Integer> numbers = IntStream.range(0, 99)
                .mapToObj(i -> i)
                .collect(Collectors.toList());

        // Your test code goes here
    }
}
```
* Implements necesary imports
* Write the test to check if the *numbers* list have exactly 100 elements

2. Extract *numbers Definition* to initialize it before test
3. Implement next tests
```java
@Test
public void shouldHaveOnlyOddNumbers() {
    // Your code goes here
}

@Test
public void shouldExtractOnlyPrimeNumbers() {
    // Your code goes here
    // Check, in another list, if this have only prime numbers
}

@Test
public void shouldSumAllNumbers() {
    // Your code goes here
    // You must iterate over numbers list. 
    // Check if the sum is equals to 4950 (0+1+2+...+99)
}

@Test
public void shouldExtractEveryPowOfTwo() {
    // Your code goes here
    // Check, in another list, if this have only numbers power of two (such as 8,16,32..)
}

@Test
public void shouldSortByPowerOfTwoFirst() {
    // Your code goes here
    // Sort the numbers list ascending first power of two then any number (ascending too)
}
```
4. Answer the questions

¿What is a Test Framework?

¿What are the steps of unit testing?

¿What is an assertion?