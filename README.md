
# JavaScript String Methods

### 1. `charAt()`
- **Purpose**: Returns the character at a specified index in a string.
- **Example**:
    ```js
    let str = "Hello";
    str.charAt(1); // "e"
    ```

### 2. `charCodeAt()`
- **Purpose**: Returns the Unicode of the character at a specified index in a string.
- **Example**:
    ```js
    let str = "Hello";
    str.charCodeAt(1); // 101 (Unicode for 'e')
    ```

### 3. `concat()`
- **Purpose**: Combines two or more strings into one.
- **Example**:
    ```js
    let str1 = "Hello";
    let str2 = "World";
    str1.concat(" ", str2); // "Hello World"
    ```

### 4. `includes()`
- **Purpose**: Determines whether one string contains another substring.
- **Returns**: `true` or `false`.
- **Example**:
    ```js
    let str = "Hello World";
    str.includes("World"); // true
    ```

### 5. `endsWith()`
- **Purpose**: Determines whether a string ends with a specified substring.
- **Example**:
    ```js
    let str = "Hello World";
    str.endsWith("World"); // true
    ```

### 6. `indexOf()`
- **Purpose**: Returns the index of the first occurrence of a specified substring, or `-1` if not found.
- **Example**:
    ```js
    let str = "Hello World";
    str.indexOf("World"); // 6
    ```

### 7. `lastIndexOf()`
- **Purpose**: Returns the index of the last occurrence of a specified substring.
- **Example**:
    ```js
    let str = "Hello World World";
    str.lastIndexOf("World"); // 12
    ```

### 8. `match()`
- **Purpose**: Retrieves the result of matching a string against a regular expression.
- **Example**:
    ```js
    let str = "Hello World";
    str.match(/World/); // ["World"]
    ```

### 9. `repeat()`
- **Purpose**: Returns a new string with a specified number of copies of the string.
- **Example**:
    ```js
    let str = "Hello";
    str.repeat(3); // "HelloHelloHello"
    ```

### 10. `replace()`
- **Purpose**: Replaces a specified substring or regex match with a new substring.
- **Example**:
    ```js
    let str = "Hello World";
    str.replace("World", "JavaScript"); // "Hello JavaScript"
    ```

### 11. `search()`
- **Purpose**: Searches for a specified value or regular expression and returns the position of the match.
- **Example**:
    ```js
    let str = "Hello World";
    str.search("World"); // 6
    ```

### 12. `slice()`
- **Purpose**: Extracts a part of a string and returns it as a new string.
- **Example**:
    ```js
    let str = "Hello World";
    str.slice(0, 5); // "Hello"
    ```

### 13. `split()`
- **Purpose**: Splits a string into an array of substrings based on a delimiter.
- **Example**:
    ```js
    let str = "Hello World";
    str.split(" "); // ["Hello", "World"]
    ```

### 14. `startsWith()`
- **Purpose**: Determines whether a string starts with a specified substring.
- **Example**:
    ```js
    let str = "Hello World";
    str.startsWith("Hello"); // true
    ```

### 15. `substr()`
- **Purpose**: Extracts a part of a string, starting from a specified index for a given length.
- **Example**:
    ```js
    let str = "Hello World";
    str.substr(6, 5); // "World"
    ```

### 16. `substring()`
- **Purpose**: Returns the part of the string between the start and end indexes.
- **Example**:
    ```js
    let str = "Hello World";
    str.substring(0, 5); // "Hello"
    ```

### 17. `toLowerCase()`
- **Purpose**: Converts a string to lowercase.
- **Example**:
    ```js
    let str = "Hello World";
    str.toLowerCase(); // "hello world"
    ```

### 18. `toUpperCase()`
- **Purpose**: Converts a string to uppercase.
- **Example**:
    ```js
    let str = "Hello World";
    str.toUpperCase(); // "HELLO WORLD"
    ```

### 19. `trim()`
- **Purpose**: Removes whitespace from both sides of a string.
- **Example**:
    ```js
    let str = "  Hello World  ";
    str.trim(); // "Hello World"
    ```

### 20. `valueOf()`
- **Purpose**: Returns the primitive value of a string object.
- **Example**:
    ```js
    let str = new String("Hello");
    str.valueOf(); // "Hello"
    ```

### Thank You!!
