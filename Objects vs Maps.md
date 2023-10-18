|                  Maps                   |            Objects             |
|:---------------------------------------:|:------------------------------:|
|      **Elements** are **ordered**       | **Elements** are **unordered** |
|              **Iterable**               |        **Not Iterable**        |
| **Key** can be **string, function, object** |   **Key** can only be **string**   |
| **Size** accessible with ***size***|   **Size** not accessible                             |

- **Elements** are **ordered in a Map** while there are **unordered in Objects**.
- Since the elements are ordered in a **Map**, it is **iterable** easily. Whereas for **Objects** we have to first get the list of all the keys to iterate through the Object.
- A key in a **Map** can be a **function, object, symbol, string**. Whereas in an **Object**, a key can only be a **string**. 
- The **size** of a **Map** can be accessed directly by reading the ***size*** property. Whereas for an **Object**, we need to **calculate the size manually**.