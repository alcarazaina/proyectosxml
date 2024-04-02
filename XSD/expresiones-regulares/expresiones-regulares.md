| Símbolo | Explicación | Ejemplo |
|---------|-------------|---------|
| .       | Coincide con cualquier carácter excepto un salto de línea. | `a.b` coincide con "aab", "acb", "adb", etc. |
| *       | Coincide con cero o más repeticiones del elemento anterior. | `a*b` coincide con "b", "ab", "aab", etc. |
| +       | Coincide con una o más repeticiones del elemento anterior. | `a+b` coincide con "ab", "aab", "aaab", etc. |
| ?       | Coincide con cero o una repetición del elemento anterior. | `a?b` coincide con "b" y "ab". |
| []      | Coincide con cualquier carácter dentro de los corchetes. | `[abc]` coincide con "a", "b" o "c". |
| [^]     | Coincide con cualquier carácter que no esté dentro de los corchetes. | `[^abc]` coincide con cualquier carácter excepto "a", "b" o "c". |
| ()      | Agrupa elementos en una expresión regular. | `(ab)+` coincide con "ab", "abab", "ababab", etc. |
| \|      | Coincide con cualquiera de las expresiones separadas por el símbolo. | `a\|b` coincide con "a" o "b". |
| \       | Escapa un carácter especial para que sea tratado literalmente. | `\.` coincide con el carácter ".". |
| {}      | Especifica un rango de repeticiones del elemento anterior. | `a{2,4}` coincide con "aa", "aaa" o "aaaa". |
| ^       | Coincide con el inicio de una línea. | `^abc` coincide con "abc" al inicio de una línea. |
| $       | Coincide con el final de una línea. | `abc$` coincide con "abc" al final de una línea. |
| \d      | Coincide con cualquier dígito. | `\d{3}` coincide con cualquier secuencia de tres dígitos. |
| \w      | Coincide con cualquier carácter alfanumérico. | `\w+` coincide con una o más letras o dígitos. |
| \s      | Coincide con cualquier espacio en blanco. | `a\sb` coincide con "a b" o "a   b". |
| \b      | Coincide con un límite de palabra. | `\bword\b` coincide con "word" como una palabra completa. |
| \A      | Coincide con el inicio de una cadena. | `\Aabc` coincide con "abc" al inicio de una cadena. |
| \Z      | Coincide con el final de una cadena. | `abc\Z` coincide con "abc" al final de una cadena. |
