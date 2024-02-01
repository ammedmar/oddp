# Best practices

1. Use `\colon` instead of `:` for defining functions.

2. Leave space around most operators. For example, `f \colon X \to Y` is superior to `f:X\to Y`. Possible exceptions are guided by readability, for example:

   ```latex
   \begin{equation}
       \sum_{i=1}^n = \frac{n(n+1)}{2}.
   \end{equation}
   ```

3. No punctuation inside math mode. Use `$a+b$,` instead of `$a+b,$`.

4. No line breaks in the middle of sentences.

5. Use line breaks at the end of sentences.

6. No double blank spaces or trailing blank spaces.

7. No blank spaces at the end of sentences.

8. Use tab instead of blank spaces for indentation.

9. All named environments with the possible exception of `document` should be tabbed. For example,

   ```latex
   \begin{lemma*}
       Statement.
   \end{lemma*}
   ```

10. Do not use `$$...$$` for display equations; instead, use one of the environments in the AMS display equation family or

    ```latex
    \[
    \]
    ```

11. Leave a blank line before and after most environments. Possible exceptions are AMS display equation family.

12. Leave a blank line before and after sections and subsections.
